## 0.15.5
* Thanks to PR from [AutonomicCoder](https://github.com/AutonomicCoder) [bug #21](https://github.com/Microsoft/vscode-mono-debug/issues/21) got fixed and mono-debug now supports protocol logging to a file.

## 0.15.4
* Mono-debug now uses the terminal service provided by VS Code. You can now use the launch config attribute `console` for selecting one of `internalConsole`, `integratedTerminal`, `externalTerminal`. The 'integratedTerminal' and 'externalTerminal' can be further configured through workspace or user settings.
* Added support for configuring handled and unhandled exceptions. Use the "Debug: Configure Exceptions" command.

## 0.15.3
* Combined 'argument' scope with 'locals' scope in variables view
* Enabled support for Windows by removing dependency on SDB, thanks for the PR from [t-h-e](https://github.com/t-h-e) - [Microsoft/vscode-mono-debug#15](https://github.com/Microsoft/vscode-mono-debug/pull/15)

## 0.14.0
* Removed curly braces from variable values
* Added CSX to debuggable extensions, thanks for the PR from [filipw](https://github.com/filipw) - [Microsoft/vscode-mono-debug#22](https://github.com/Microsoft/vscode-mono-debug/pull/22)

## 0.13.0
* Enable support for showing variables values in source while stepping
