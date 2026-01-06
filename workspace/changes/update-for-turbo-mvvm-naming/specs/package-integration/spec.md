# Spec: Package Integration

## MODIFIED Requirements

### Requirement: turbo_notifiers Example Uses TurboViewModel
The `turbo_notifiers` example code MUST use `TurboViewModel` and `TurboViewModelBuilder` (renamed from `BaseViewModel` and `ViewModelBuilder`) from `turbo_mvvm` package.

#### Scenario: Example uses TurboViewModel
- **WHEN** `turbo_notifiers` example code uses MVVM pattern
- **THEN** it uses `TurboViewModel` (not `BaseViewModel`)
- **AND** it uses `TurboViewModelBuilder` (not `ViewModelBuilder`)
- **AND** all imports reference `package:turbo_mvvm/turbo_mvvm.dart`

