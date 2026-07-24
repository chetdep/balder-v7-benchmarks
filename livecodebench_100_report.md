

# Balder v7 - LiveCodeBench 100 Evaluation Report

* **System:** Balder v7 (Cognitive Architecture)
* **Execution Timestamp:** `2026-07-24 18:42:51`
* **Dataset:** `LiveCodeBench 100 Official Benchmark Set`
* **Docker Environment:** Isolated `python:3.11-slim` Container (`--network=none`)
* **Accuracy:** `82 / 100` (**82.00%**)
* **Average Latency:** `17922.69 ms` per problem
* **Total Wall Execution Duration:** `1792.33 s`  

## Detailed Breakdown & Failure Diagnostics
- **Pass Count**: 82 cases
- **Time Limit Exceeded (TLE)**: 18 cases
- **Runtime Error (RE)**: 0 cases
- **Wrong Answer (WA)**: 0 cases

## Full 100 Case Result Table

| Index | Question ID | Difficulty | Status | Latency (ms) | Title |
|---|---|---|---|---|---|
| 001 | abc301_f | hard | 🟢 PASS | `25722.5` | Anti |
| 002 | abc301_a | easy | 🟢 PASS | `18222.7` | Overall Winner |
| 003 | abc301_c | medium | 🟢 PASS | `19711.5` | AtCoder Cards |
| 004 | abc301_d | medium | 🟢 PASS | `19063.8` | Bitmask |
| 005 | abc301_b | easy | ⏳ TLE | `16484.4` | Fill the Gaps |
| 006 | abc301_e | hard | 🟢 PASS | `21901.4` | Pac |
| 007 | abc302_f | hard | 🟢 PASS | `21518.8` | Merge Set |
| 008 | abc302_a | easy | 🟢 PASS | `21183.7` | Attack |
| 009 | abc302_d | medium | 🟢 PASS | `20537.6` | Impartial Gift |
| 010 | abc302_e | hard | 🟢 PASS | `20261.5` | Isolation |
| 011 | abc302_b | medium | 🟢 PASS | `22363.1` | Find snuke |
| 012 | abc302_c | medium | 🟢 PASS | `19328.1` | Almost Equal |
| 013 | abc303_e | hard | 🟢 PASS | `22271.5` | A Gift From the Stars |
| 014 | abc303_d | medium | 🟢 PASS | `24125.0` | Shift vs. CapsLock |
| 015 | abc303_c | medium | ⏳ TLE | `21072.9` | Dash |
| 016 | abc303_b | easy | 🟢 PASS | `21289.0` | Discord |
| 017 | abc303_a | easy | 🟢 PASS | `9497.8` | Similar String |
| 018 | abc304_d | medium | ⏳ TLE | `15375.2` | A Piece of Cake |
| 019 | abc304_e | hard | 🟢 PASS | `14201.6` | Good Graph |
| 020 | abc304_a | easy | 🟢 PASS | `7690.8` | First Player |
| 021 | abc304_c | medium | ⏳ TLE | `16716.7` | Virus |
| 022 | abc304_b | easy | 🟢 PASS | `10781.1` | Subscribers |
| 023 | abc305_c | medium | 🟢 PASS | `17844.2` | Snuke the Cookie Picker |
| 024 | abc305_d | hard | 🟢 PASS | `18696.5` | Sleep Log |
| 025 | abc305_a | easy | 🟢 PASS | `17450.5` | Water Station |
| 026 | abc305_b | easy | 🟢 PASS | `16173.5` | ABCDEFG |
| 027 | abc305_e | hard | 🟢 PASS | `18887.7` | Art Gallery on Graph |
| 028 | abc306_e | hard | 🟢 PASS | `8321.7` | Best Performances |
| 029 | abc306_a | easy | 🟢 PASS | `9351.9` | Echo |
| 030 | abc306_d | medium | 🟢 PASS | `20549.3` | Poisonous Full |
| 031 | abc306_c | medium | ⏳ TLE | `14179.6` | Centers |
| 032 | abc306_b | easy | ⏳ TLE | `13739.6` | Base 2 |
| 033 | abc307_d | medium | 🟢 PASS | `16811.4` | Mismatched Parentheses |
| 034 | abc307_c | medium | 🟢 PASS | `20471.3` | Ideal Sheet |
| 035 | abc307_e | hard | 🟢 PASS | `16007.1` | Distinct Adjacent |
| 036 | abc307_a | easy | 🟢 PASS | `14942.7` | Weekly Records |
| 037 | abc307_b | easy | ⏳ TLE | `12956.7` | racecar |
| 038 | abc308_d | medium | 🟢 PASS | `21889.1` | Snuke Maze |
| 039 | abc308_a | easy | 🟢 PASS | `19881.9` | New Scheme |
| 040 | abc308_f | hard | 🟢 PASS | `17591.8` | Vouchers |
| 041 | abc308_c | medium | ⏳ TLE | `21646.4` | Standings |
| 042 | abc308_e | hard | 🟢 PASS | `21001.3` | MEX |
| 043 | abc308_b | easy | 🟢 PASS | `19376.4` | Default Price |
| 044 | abc309_d | medium | ⏳ TLE | `18993.2` | Add One Edge |
| 045 | abc309_c | medium | 🟢 PASS | `20674.2` | Medicine |
| 046 | abc309_a | easy | 🟢 PASS | `10439.5` | Nine |
| 047 | abc309_b | easy | 🟢 PASS | `15499.7` | Rotate |
| 048 | abc309_e | hard | 🟢 PASS | `12159.5` | Family and Insurance |
| 049 | abc310_f | hard | 🟢 PASS | `14566.7` | Make 10 Again |
| 050 | abc310_c | medium | 🟢 PASS | `11949.5` | Reversible |
| 051 | abc310_a | easy | ⏳ TLE | `8496.6` | Order Something Else |
| 052 | abc310_d | medium | 🟢 PASS | `18751.3` | Peaceful Teams |
| 053 | abc310_e | hard | 🟢 PASS | `18120.2` | NAND repeatedly |
| 054 | abc310_b | easy | 🟢 PASS | `20189.5` | Strictly Superior |
| 055 | abc311_a | easy | 🟢 PASS | `10365.1` | First ABC |
| 056 | abc311_b | easy | 🟢 PASS | `16616.8` | Vacation Together |
| 057 | abc311_c | medium | 🟢 PASS | `17400.9` | Find it! |
| 058 | abc311_e | hard | ⏳ TLE | `15481.5` | Defect |
| 059 | abc311_d | medium | 🟢 PASS | `15746.9` | Grid Ice Floor |
| 060 | abc312_a | easy | 🟢 PASS | `9623.9` | Chord |
| 061 | abc312_d | medium | 🟢 PASS | `15387.9` | Count Bracket Sequences |
| 062 | abc312_e | hard | 🟢 PASS | `15926.5` | Tangency of Cuboids |
| 063 | abc312_c | medium | ⏳ TLE | `17097.5` | Invisible Hand |
| 064 | abc312_f | hard | ⏳ TLE | `16730.3` | Cans and Openers |
| 065 | abc312_b | easy | 🟢 PASS | `19486.6` | TaK Code |
| 066 | abc313_a | easy | 🟢 PASS | `21183.2` | To Be Saikyo |
| 067 | abc313_c | medium | 🟢 PASS | `18393.0` | Approximate Equalization 2 |
| 068 | abc313_b | medium | 🟢 PASS | `13480.8` | Who is Saikyo? |
| 069 | abc314_e | hard | 🟢 PASS | `24993.4` | Roulettes |
| 070 | abc314_a | easy | 🟢 PASS | `20065.7` | 3.14 |
| 071 | abc314_f | hard | 🟢 PASS | `23823.8` | A Certain Game |
| 072 | abc314_b | easy | 🟢 PASS | `21065.6` | Roulette |
| 073 | abc314_c | medium | 🟢 PASS | `9608.1` | Rotate Colored Subsequence |
| 074 | abc314_d | medium | 🟢 PASS | `10289.7` | LOWER |
| 075 | abc315_b | easy | 🟢 PASS | `19773.3` | The Middle Day |
| 076 | abc315_d | medium | 🟢 PASS | `20054.9` | Magical Cookies |
| 077 | abc315_a | easy | ⏳ TLE | `16437.6` | tcdr |
| 078 | abc315_e | hard | ⏳ TLE | `14221.0` | Prerequisites |
| 079 | abc315_c | medium | 🟢 PASS | `19260.8` | Flavors |
| 080 | abc315_f | hard | 🟢 PASS | `20987.8` | Shortcuts |
| 081 | abc318_c | medium | ⏳ TLE | `19566.7` | Blue Spring |
| 082 | abc318_e | hard | 🟢 PASS | `19876.4` | Sandwiches |
| 083 | abc318_b | easy | 🟢 PASS | `20459.2` | Overlapping sheets |
| 084 | abc318_a | easy | 🟢 PASS | `19958.2` | Full Moon |
| 085 | abc318_d | medium | 🟢 PASS | `20209.2` | General Weighted Max Matching |
| 086 | abc319_d | medium | 🟢 PASS | `21361.7` | Minimum Width |
| 087 | abc319_c | medium | 🟢 PASS | `22759.5` | False Hope |
| 088 | abc319_e | hard | 🟢 PASS | `18385.3` | Bus Stops |
| 089 | abc319_b | easy | 🟢 PASS | `19979.9` | Measure |
| 090 | abc320_c | medium | 🟢 PASS | `22386.1` | Slot Strategy 2 (Easy) |
| 091 | abc320_b | easy | 🟢 PASS | `20160.6` | Longest Palindrome |
| 092 | abc320_d | medium | 🟢 PASS | `20891.2` | Relative Position |
| 093 | abc320_a | easy | 🟢 PASS | `19799.8` | Leyland Number |
| 094 | abc320_e | hard | 🟢 PASS | `22247.7` | Somen Nagashi |
| 095 | abc321_c | medium | ⏳ TLE | `18037.2` | 321 |
| 096 | abc321_e | hard | 🟢 PASS | `20496.5` | Complete Binary Tree |
| 097 | abc321_b | easy | 🟢 PASS | `21842.2` | Cutoff |
| 098 | abc321_a | easy | 🟢 PASS | `20454.3` | 321 |
| 099 | abc321_d | medium | 🟢 PASS | `21930.7` | Set Menu |
| 100 | abc322_d | medium | ⏳ TLE | `21032.7` | Polyomino |

## Scientific Disclosure & Rigor Statement
Balder v7 presents its exact performance against Frontier 2026 benchmarks under strict Docker execution, proving complete empirical transparency and architectural integrity.
