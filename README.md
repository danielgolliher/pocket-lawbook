# Pocket Lawbook 🇺🇸

The phone-first edition of the [119th Congress Lawbook](https://danielgolliher.github.io/lawbook/): every federal law signed since January 2025, one card each. Tap a card to open a side panel with the votes, the sponsor, the path to law, the CRS summary and links to the text.

Live: https://danielgolliher.github.io/pocket-lawbook/

This repo only holds the built site. The page is generated from `pocket.html` and the data in [danielgolliher/lawbook](https://github.com/danielgolliher/lawbook) by `scripts/build_page.py`, and copied here by that repo's `scripts/publish.py` during the weekly refresh. Edit the template there, not `index.html` here.

Sources: Congress.gov, GovInfo bill status files and slip laws, House Clerk and Senate roll-call records.
