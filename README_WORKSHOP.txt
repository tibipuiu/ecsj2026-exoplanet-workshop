EXOPLANET PLAYGROUND — ECSJ 2026 WORKSHOP KIT

FILES
- Official EFSJ and ZME Science logos are built into the HTML (no external images needed).
- exoplanet_playground.html: The self-contained, one-page interactive microsite.
- dataset.csv: The full NASA Exoplanet Archive workshop snapshot.
- PUBLISH_WITH_CHATGPT_SITES.txt: Instructions for making a public ChatGPT-hosted site.

QUICK START
Open exoplanet_playground.html in an up-to-date Chrome, Firefox, Edge, or Safari.
Choose a calling card, adjust the two text fields, and copy the master prompt into a chatbot.
The "Download NASA dataset.csv" button works offline: the CSV is embedded in compressed form in the HTML.
The original standalone dataset.csv is also included in this ZIP.

FOR SHARING WITH ATTENDEES
ChatGPT Sites can publish a hosted site. Open https://chatgpt.com/sites or switch to Work on ChatGPT web. Upload this kit and use the included ChatGPT Sites deployment brief. Preview and verify functionality before choosing Share > Anyone on the Internet (if available) > Publish > Copy link. ChatGPT-hosted Site URLs may use a .chatgpt.site address. Publishing requires user action and access to Sites.
Alternative: host the standalone HTML on GitHub Pages or another static host. The page includes its own dataset and needs no backend.

WORKSHOP CONSTRAINTS FOR ATTENDEES
One index.html with embedded CSS and JavaScript. No server, APIs, dependency managers, frameworks, or external libraries.
Load the dataset via browser file picker. Use default_flag=1 for one record per planet. Treat missing values as unknown.

WORKSHOP DATASET VERIFICATION
Rows: 40,194. Unique planets with default_flag=1: 6,375. Unique host stars: 4,780. Discovery methods: 11.
Source: https://exoplanetarchive.ipac.caltech.edu/
Archive DOI: 10.26133/NEA1
