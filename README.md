# Polymarket CTF Exchange V2

## Development

Install [Foundry](https://github.com/foundry-rs/foundry/).

Foundry has daily updates, run `foundryup` to update `forge` and `cast`.

---

## Testing

To run all tests: `forge test`

To run test functions matching a regex pattern `forge test -m PATTERN`

To run tests in contracts matching a regex pattern `forge test --mc PATTERN`

Set `-vvv` to see a stack trace for a failed test.

---

To install new foundry submodules: `forge install UserName/RepoName@CommitHash`

To remove: `forge remove UserName/RepoName`

