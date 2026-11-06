# FastPDFimg.com

Free, browser-only PDF & image tools (Merge, Compress, Split, JPG→PDF, PDF→Word/Excel/JPG, OCR, Photo→X KB).
Files never leave the user's device. Static site – hosted on GitHub Pages.

## Upload steps (GitHub Pages)
1. GitHub पर नई **public** repository बनाएँ (जैसे `fastpdfimg`).
2. इस folder की **सारी files और `libs` folder** repo में upload करें (Add file → Upload files). `index.html` root में होनी चाहिए.
3. Settings → Pages → Source: *Deploy from a branch* → Branch: `main` / `(root)` → Save.
4. 1-2 मिनट में site `https://USERNAME.github.io/REPO/` पर चालू.
5. Custom domain हो तो Pages → Custom domain में डालें और DNS में CNAME/A records लगाएँ; "Enforce HTTPS" चालू करें.

## Launch से पहले ज़रूर बदलें
- `YOUR-EMAIL-HERE` → अपना असली email (`privacy.html`, `terms.html`, `about.html` में).
- `https://fastpdfimg.com` → अपना असली पता (github.io या असली domain) — सभी `.html`, `sitemap.xml`, `robots.txt` में find & replace.

## Google में दिखाने के लिए
1. Google Search Console में site जोड़ें → `sitemap.xml` submit करें.
2. Bing Webmaster Tools में भी यही.

## Licenses
Open-source libraries `libs/` में हैं; उनके license `libs/licenses/` में और `licenses.html` पेज पर. Repo में अपना LICENSE न डालने पर code पर डिफ़ॉल्ट रूप से आपके सारे अधिकार सुरक्षित रहते हैं.
