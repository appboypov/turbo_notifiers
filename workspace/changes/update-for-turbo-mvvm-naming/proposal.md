# Change: Update turbo_notifiers example to use TurboViewModel

## Why
After `turbo_mvvm` package renamed `BaseViewModel` to `TurboViewModel` and `ViewModelBuilder` to `TurboViewModelBuilder`, `turbo_notifiers` example must be updated to use the new class names to prevent broken imports and maintain consistency.

## What Changes
- Update `turbo_notifiers/example/lib/main.dart` to use `TurboViewModel` (renamed from `BaseViewModel`)
- Update `turbo_notifiers/example/lib/main.dart` to use `TurboViewModelBuilder` (renamed from `ViewModelBuilder`)

## Impact
- Affected code:
  - `turbo_notifiers/example/lib/main.dart`

