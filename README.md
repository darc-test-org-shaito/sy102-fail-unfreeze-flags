# sy102-fail-unfreeze-flags

DARC test fixture for the SY-1.02 scan. The workflows first carried explicit
unfreeze flags and the scan failed them. They now use the frozen forms
(`pnpm install --frozen-lockfile`, `yarn install --immutable`,
`bun install --frozen-lockfile`), so the expected result is `pass`.
