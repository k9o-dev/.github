# Kilimanjaro

**Build AI-native apps on a governed foundation.** Data, security, governance and compute in one architecture, with four products on top.

| Product | What it does | Key capabilities |
|---|---|---|
| **Keep** | AI Security and Governance | AI trust, risk and security management for agents |
| **Pulse** | Data Intelligence | A data intelligence plane for operational and agentic systems, with federated analytics and an event bus |
| **Gate** | Customer Identity and Access Management | Authentication, authorization and identity federation |
| **Kibo** | Keys and Secrets Management | Custody modes, bring-your-own-key (BYOK) and hold-your-own-key (HYOK) |

## Links

- Website: <https://kilimanjaro.dev>
- Documentation / Developer Hub: <https://docs.kilimanjaro.dev>
- Platform API: <https://api.k9o.io>
- Platform Console: <https://console.k9o.io>

## Start here: SDKs and CLI

| Language | Package | Install | Repository |
|---|---|---|---|
| TypeScript / JavaScript | `@k9o/core` | `npm install @k9o/core` | [sdk-typescript](https://github.com/k9o-dev/sdk-typescript) |
| Python | `k9o` | `pip install k9o` | [sdk-python](https://github.com/k9o-dev/sdk-python) |
| Command line | `@k9o/cli` | `npm install -g @k9o/cli` | [cli](https://github.com/k9o-dev/cli) |
| Go | `k9o.dev/sdk-go` | `go get k9o.dev/sdk-go` | [sdk-go](https://github.com/k9o-dev/sdk-go) |
| Java | `dev.k9o:core` | Maven or Gradle, see the README | [sdk-java](https://github.com/k9o-dev/sdk-java) |
| .NET | `K9o.Core` | `dotnet add package K9o.Core` | [sdk-dotnet](https://github.com/k9o-dev/sdk-dotnet) |
| Rust | `k9o` | `cargo add k9o` | [sdk-rust](https://github.com/k9o-dev/sdk-rust) |
| Ruby | `k9o` | `gem install k9o` | [sdk-ruby](https://github.com/k9o-dev/sdk-ruby) |
| PHP | `k9o/sdk` | `composer require k9o/sdk` | [sdk-php](https://github.com/k9o-dev/sdk-php) |
| Swift | Swift package | Add `https://github.com/k9o-dev/sdk-swift` | [sdk-swift](https://github.com/k9o-dev/sdk-swift) |
| Flutter | `k9o_gate` | `flutter pub add k9o_gate` | [pub.dev](https://pub.dev/packages/k9o_gate) |
| React Native | `@k9o/gate-react-native` | `npm install @k9o/gate-react-native` | [npm](https://www.npmjs.com/package/@k9o/gate-react-native) |
| Kotlin / Android | | First release in progress | [sdk-kotlin](https://github.com/k9o-dev/sdk-kotlin) |

### Kibo: client-side encryption with keys you hold

Kibo packages encrypt and decrypt on your own machine or device against your own key management service, so the platform never sees plaintext or unwrapped keys.

| Platform | Package |
|---|---|
| TypeScript | `@k9o/kibo` |
| .NET | `K9o.Kibo` |
| Go | `k9o.dev/sdk-go/kibo` |
| Swift | [sdk-kibo-swift](https://github.com/k9o-dev/sdk-kibo-swift) |
| React Native | `@k9o/kibo-react-native` |

## How these repositories work

Each repository is published from our monorepo and replaced with every release, which is why the history is one commit per release. Open issues here. Fixes ship in the next release. See [CONTRIBUTING](https://github.com/k9o-dev/.github/blob/main/CONTRIBUTING.md) for the details.

## Help

Questions and bugs: open an issue on the repository for your language, or email <help@kilimanjaro.dev>.
