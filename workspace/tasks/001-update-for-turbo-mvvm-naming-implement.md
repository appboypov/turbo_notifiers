---
status: done
skill-level: junior
parent-type: change
parent-id: update-for-turbo-mvvm-naming
---

# Task: Update turbo_notifiers example to use TurboViewModel

## End Goal
Update `turbo_notifiers` example code to use `TurboViewModel` and `TurboViewModelBuilder` (renamed from `BaseViewModel` and `ViewModelBuilder`).

## Currently
- Example uses `BaseViewModel`
- Example uses `ViewModelBuilder`

## Should
- Example uses `TurboViewModel`
- Example uses `TurboViewModelBuilder`
- All imports reference `package:turbo_mvvm/turbo_mvvm.dart`

## Constraints
- Must update class usage: `BaseViewModel` → `TurboViewModel`
- Must update widget usage: `ViewModelBuilder` → `TurboViewModelBuilder`
- Must preserve all functionality
- Must verify example compiles

## Acceptance Criteria
- [x] `turbo_notifiers/example/lib/main.dart` updated to use `TurboViewModel` and `TurboViewModelBuilder`
- [x] Example compiles without errors

## Implementation Checklist
- [x] 1.1 Update `turbo_notifiers/example/lib/main.dart`: `BaseViewModel` → `TurboViewModel`
- [x] 1.2 Update `turbo_notifiers/example/lib/main.dart`: `ViewModelBuilder` → `TurboViewModelBuilder`
- [x] 1.3 Verify example compiles: `cd turbo_notifiers && flutter pub get && flutter analyze`

## Notes
- Simple rename in example code, no behavior changes

