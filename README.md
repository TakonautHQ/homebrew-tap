# Takonaut Homebrew Tap

Official Homebrew formulae for [Takonaut](https://takonaut.com).

## Install Tako Runner

Install the formula directly. Homebrew will add the tap and trust only the Tako Runner formula:

```bash
brew install TakonautHQ/tap/tako-runner
```

If you add the tap separately, explicitly trust only this formula before using its short name:

```bash
brew tap TakonautHQ/tap
brew trust --formula TakonautHQ/tap/tako-runner
brew install tako-runner
```

Configure the Runner after installation:

```bash
tako-runner setup
```

To run it as a managed background service:

```bash
brew services start tako-runner
```

## Upgrade

```bash
brew update
brew upgrade tako-runner
```

## Stop or uninstall

```bash
brew services stop tako-runner
brew uninstall tako-runner
brew untap TakonautHQ/tap
```

## Formulae

| Formula | Description | Source |
| --- | --- | --- |
| `tako-runner` | Customer-managed Takonaut Project Agent Runner powered by Pi | [TakonautHQ/tako-runner](https://github.com/TakonautHQ/tako-runner) |

## Security

Report vulnerabilities privately according to the [Tako Runner security policy](https://github.com/TakonautHQ/tako-runner/security/policy). Do not open public issues for suspected vulnerabilities.

## License

Apache License 2.0. See [LICENSE](LICENSE).
