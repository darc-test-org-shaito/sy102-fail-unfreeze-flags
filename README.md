# sy102-fail-unfreeze-flags

DARC test fixture for the SY-1.02 scan. Expected result: `fail` naming
"2 of 2 workflow file(s)". Each workflow switches freezing off with an
explicit flag: `--no-frozen-lockfile`, `--no-immutable`,
`--frozen-lockfile=false`.
