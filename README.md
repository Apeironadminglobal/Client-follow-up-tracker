# Client Follow-Up Tracker

A simple web form for tracking client proposals and follow-ups, with one-click export to Excel.

**Columns:** Client Name, Company, Proposal, First Follow Up, 2nd Follow Up, 3rd Follow Up

## Use
1. Fill in the form and click **Add Client**.
2. Edit the follow-up dates in the table as you follow up.
3. Click **Export to Excel** to download `Client_Follow_Up_Tracker.xlsx`.

## Notes
- Data is saved in your browser (localStorage) on the device you use. It is not shared between devices or people, so export regularly as a backup.
- Excel export uses [SheetJS](https://sheetjs.com/) loaded from cdnjs, so an internet connection is needed on first load.

## Host on GitHub Pages
1. Create a new repository and upload `index.html` and this `README.md`.
2. Go to **Settings → Pages**, set the source to **Deploy from a branch**, choose `main` and `/ (root)`, then save.
3. After a minute, your site is live at `https://<your-username>.github.io/<repo-name>/`.
