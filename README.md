# Stock Buybacks: Who Benefits?

HE4045 Group 10: Goh Yee Xi, Ong Zheng Yang James, Tan Jin Yenn, Tay Jian Yuan

Do US firms that buy back more of their own shares earn higher stock returns in the 3 months after the buyback is made public? We use Compustat and CRSP data from 2010 to 2025 and panel regressions with fixed effects.

## Files
- `HE4045_Group 10_Final Project.pdf`: final report
- `HE4045_Group+10_Mid-Semester+Project+Proposal+.pdf`: project proposal
- `HE4045_Group10_Buybacks_Returns_Only.ipynb`: code that rebuilds every number, table and figure in the report

## How to run
1. `pip install -r requirements.txt`
2. You need a WRDS account with access to Compustat, CRSP and the Fama-French factors. Put your login in a `.env` file next to the notebook:
   ```
   WRDS_USERNAME=...
   WRDS_PASSWORD=...
   ```
3. Open the notebook, set `DOWNLOAD_DATA = True` for the first run, and run all cells. The data is saved to `data/`.

The WRDS data itself is not included, because its license does not allow sharing it.
