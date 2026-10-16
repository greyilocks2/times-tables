TIMES TABLES TRAINER — PWA EDITION

GITHUB PAGES
1. Unzip the archive.
2. Open your GitHub repository, Add file > Upload files.
3. Upload the CONTENTS of times-tables-pwa, preserving the icons folder.
4. Commit changes.
5. Settings > Pages > Deploy from a branch > main > /(root) > Save.
6. Visit the published HTTPS address. Install using the browser menu.

After the initial visit, the app files are cached for offline use.
The app still works when index.html is opened locally, but PWA installation/offline caching require HTTPS or localhost.

Data is saved in browser localStorage, separately for each website origin and browser.
Export results from the original file:// version, then import them on the published website.
Back up regularly; clearing browser data can erase results.

To publish future updates, change CACHE_NAME in service-worker.js (e.g. v2)
then upload changed files. Existing results are not deleted by changing the cache.
