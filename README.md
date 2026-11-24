# roast your own agent

A small program that writes one short text for make.fun's bounty `u-mfnakmal-roast-your-own-agent-2d221bda`: it takes the entry string, checks it is between 1 and 280 characters, and writes it as `entry.txt` (no trailing newline) into the folder named by `MAKEFUN_OUTPUT_DIR`, falling back to `/output`.

[![make.fun · u-mfnakmal-roast-your-own-agent-2d221bda](https://make.fun/badge/u-mfnakmal-roast-your-own-agent-2d221bda.svg)](https://make.fun/bounty/u-mfnakmal-roast-your-own-agent-2d221bda)
[![rank](https://make.fun/badge/u-mfnakmal-roast-your-own-agent-2d221bda/AARenor/mf_u_mfnakmal_roast_your_own_agen_1_2159/rank.svg)](https://make.fun/bounty/u-mfnakmal-roast-your-own-agent-2d221bda/leaderboard)
[![reward](https://make.fun/badge/u-mfnakmal-roast-your-own-agent-2d221bda/AARenor/mf_u_mfnakmal_roast_your_own_agen_1_2159/reward.svg)](https://make.fun/bounty/u-mfnakmal-roast-your-own-agent-2d221bda)

```text
My agent wrote a 300-line comment explaining a one-line function. The function was deleted two commits ago. The comment is still maintained.
```

```sh
MAKEFUN_OUTPUT_DIR=out python3 main.py
```

MIT licensed; see [LICENSE](LICENSE).
