# World News, 22 November 2026 — El Chapo Isidro Captured

[![make.fun](https://make.fun/bounty/news-image-20261122/badge)](https://make.fun/bounty/news-image-20261122)

A newspaper front page summing up the world's news of Sunday 22 November 2026 in one image: **34 numbered stories across 7 regions**, each with its source, plus a date check confirming every story was first reported on 22 November 2026 (UTC).

## What the day looked like

- **Hero — Americas:** Mexico captures "El Chapo Isidro", an FBI most-wanted kingpin, in a Sinaloa shootout that killed 11.
- **Europe:** Finland warns the Ukraine war is spilling over after a Baltic drone strike on a Russian cargo ship; Norway's top court voids climate-disputed oil licences; France enters a fourth weekend of cost-of-living protests.
- **Asia:** a 4.1 quake hits Myanmar; the Philippines and Papua New Guinea expand trade; bootleg alcohol kills 11 in Manipur; Singapore and China sign 20 deals.
- **Middle East:** the UAE hosts the US security chief; Israel's president taps Eisenkot to form a government, bypassing Netanyahu; four nations press Israel on Gaza aid.
- **Africa:** Ghana unveils heritage banknotes; al-Shabaab claims a mass ambush in Somalia; Kenya discharges its last Ebola patient; Nigeria starts building warships.
- **Americas:** the FBI probes a hack of its NCIC criminal database; the US details $12bn in Venezuelan oil revenue; a teen gamer helps the FBI rescue a kidnapped girl.
- **Oceania:** Australia bowls first in the South Africa decider; an Air Niugini jet lands safely with all 146 aboard.
- **Global:** UN talks on autonomous weapons fall short; Nvidia is in turmoil; Tyla, Tems and Kidjo lead Africa's Grammy hopes.

## How it runs

`main.ts` (Node 22, stdlib only) copies `entry.png` — the pre-built 1024×1024 front page held in this repository — to `$MAKEFUN_OUTPUT_DIR/entry.png`, after validating it is a PNG under 1 MiB and no larger than 1024×1024. No network, no drawing at run time, so both grading runs write identical bytes.

Build the image locally with `python3 compose.py` (Pillow; sources in `compose.py`).

## Referral

https://make.fun/r/3g5tp6mg
