# Strathmore NLP Hub Datathon 2026 | Team 9: Cheche

**Working language:** Kiswahili

**Track:** To be confirmed in the data plan

**Status:** Prototype in progress. Final submission deadline: 11 November 2026, 11:59 p.m. EAT.

## Team and roles

| Member | GitHub | Role |
|---|---|---|
| Ivy Tanui | [tanuiivy](https://github.com/tanuiivy) | TBC |
| Irene Kariuki | [IreneWanjiruKariuki](https://github.com/IreneWanjiruKariuki) | TBC |
| Cindy Wanini Gichuhi | [Waniniran](https://github.com/Waniniran) | TBC |

Roles are shared where useful, and every member's contribution is recorded in the contribution statement and in the commit history.

## What we contributed and what we reused

To be completed as the work progresses: data counts, source and permission summary, and anything reused from the starter kit or MASSIVE (kept separate from our contribution file).

## How to run

Python 3.10 or later.

```bash
python -m venv .venv
# macOS/Linux:
source .venv/bin/activate
# Windows PowerShell:
.venv\Scripts\Activate.ps1

python -m pip install -r requirements.txt
python validate.py --track intent --data data/contribution.csv
python train.py --track intent --data data/contribution.csv
python evaluate.py --track intent --data data/contribution.csv
python -m streamlit run app.py
```

## Results and limitations

To be completed after the final evaluation: test results, majority baseline, up to five analysed mistakes and known limitations.

## Credits

Built from Strathmore NLP Hub Datathon 2026 starter kit v2.0. Upstream sources and licences will be listed here as they are confirmed.

## AI-use statement

To be completed: tools used, their purpose, the work affected and the human checks applied.
