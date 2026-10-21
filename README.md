# ArchLiquid Documentation

Developer documentation index for [ArchLiquid](https://archliquid.com/).
The implementation repositories below contain the current build instructions,
contract references, and integration guides.

## EVM contracts

Start with the [composed contracts workspace](https://github.com/ArchLiquid/archliquid-contracts)
for pinned module versions, installation, integration tests, and deployment
instructions.

| Guide | Scope |
|---|---|
| [Core](https://github.com/ArchLiquid/archliquid-core#readme) | Treasury, stock registry, and constrained stock execution. |
| [Launchpad](https://github.com/ArchLiquid/archliquid-launchpad#readme) | Presales, bonding curves, and liquidity adapters. |
| [Token](https://github.com/ArchLiquid/archliquid-token#readme) | Token creation, distribution accounting, and factory integration. |
| [Lockers](https://github.com/ArchLiquid/archliquid-lockers#readme) | ERC-20 liquidity and V3/V4 position custody. |
| [Vesting](https://github.com/ArchLiquid/archliquid-vesting#readme) | Cliff and linear-release schedules. |
| [Staking](https://github.com/ArchLiquid/archliquid-staking#readme) | Pool creation, reward funding, staking, and claims. |
| [Lending](https://github.com/ArchLiquid/archliquid-lending#readme) | Market configuration, oracle pricing, and collateralized borrowing. |

The [published network manifests](https://github.com/ArchLiquid/archliquid-contracts/tree/main/deployments)
describe the recorded Robinhood Chain testnet deployments. Module `main` branches
may contain changes newer than those deployments; use the composed workspace's
lockfile and the matching release manifest when identifying deployed code.

## Solana programs and SDK

The TypeScript SDK currently targets Solana devnet. Its APIs and deployment
registry are separate from the EVM contracts.

| Guide | Scope |
|---|---|
| [SDK overview](https://github.com/ArchLiquid/archliquid-sdk#readme) | Installation, supported runtime, public APIs, and devnet scope. |
| [SDK integration](https://github.com/ArchLiquid/archliquid-sdk/blob/main/docs/integration.md) | Account snapshots, transaction plans, token accounts, and wallet integration. |
| [Quote reference fixtures](https://github.com/ArchLiquid/archliquid-sdk/blob/main/docs/reference-quotes.md) | Independent quote-fixture format and verification. |
| [SDK release validation](https://github.com/ArchLiquid/archliquid-sdk/blob/main/docs/release-validation.md) | Recorded checks and outstanding validation gates. |
| [Solana locker](https://github.com/ArchLiquid/archliquid-solana-locker#readme) | Immutable lock program, custody rules, and release verification. |

The SDK does not provide EVM ABIs or a verified mainnet deployment registry.

## Protocol overview

Read the [ArchLiquid whitepaper](https://www.archliquid.com/whitepaper) for the
protocol thesis and product concepts.

## Security

See [SECURITY.md](SECURITY.md) to report a security-sensitive documentation
issue.

## License

ArchLiquid documentation and assets are proprietary. See [LICENSE](LICENSE).
