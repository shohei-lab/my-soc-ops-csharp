# Copilot Instructions — Soc Ops

## ✅ Mandatory Development Checklist

Run **all** of these before considering any change complete. Do not skip.

```bash
# 1. Lint / format check (must report no changes)
dotnet format SocOps/SocOps.csproj --verify-no-changes

# 2. Build (must succeed with no new warnings)
dotnet build SocOps/SocOps.csproj

# 3. Test (run if any test project exists; currently none in main app)
dotnet test
```

If a step fails, fix it before moving on. Don't commit red builds.

## Project

Blazor WebAssembly (**net10.0**) social bingo game. Fully client-side, deploys to GitHub Pages via `.github/workflows/deploy.yml`.

## Layout

```
SocOps/
├── Components/   # BingoBoard, BingoSquare, BingoModal, GameScreen, StartScreen
├── Pages/        # @page-routed views (Home, etc.)
├── Layout/       # MainLayout + scoped .razor.css
├── Models/       # GameState, BingoSquareData, BingoLine
├── Services/     # BingoGameService (state) + BingoLogicService (pure logic)
├── Data/         # Questions.cs (static seed)
├── wwwroot/      # index.html, css/app.css, lib/, assets
└── Program.cs    # WASM host + DI
.github/agents|instructions|prompts|workflows
.solutions/      # Read-only reference solutions per workshop step
```

Build `SocOps/SocOps.csproj` directly — the `.sln` also builds every `.solutions/*` project.

## Conventions

- `Nullable` and `ImplicitUsings` are **enabled** — respect annotations, no redundant usings.
- PascalCase public members, `_camelCase` private fields.
- Keep **pure logic** in `BingoLogicService` (static, no side effects); **state** in `BingoGameService`.
- Components: `@code { }` block at the bottom of the `.razor` file. Scoped styles via `Component.razor.css`.
- Shared state via `BingoGameService` (registered `Scoped` in `Program.cs`); subscribe to `OnStateChanged` and unsubscribe in `Dispose`.
- Persistence: `IJSRuntime` → `localStorage` with `STORAGE_VERSION` — bump it when the persisted shape changes.

## Styling

Custom Tailwind-like utilities live in `wwwroot/css/app.css` (`.flex`, `.grid grid-cols-5`, `.gap-1`, `.bg-accent`, `.bg-marked`, `.aspect-square`, …). **Do not** add Tailwind, Bootstrap, or other CSS frameworks — extend `app.css` instead. See `.github/instructions/` for design guidance.

## Guardrails

- **Do not modify `.solutions/*`** unless the user explicitly targets a specific step.
- Don't add dependencies without a clear reason.
- Prefer the matching custom agent in `.github/agents/` (`pixel-jam`, `quiz-master`, `ui-review`, `tdd*`) when the task fits its specialty.
