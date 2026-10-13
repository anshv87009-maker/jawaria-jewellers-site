JAWARIYA JEWELLERS — RINGS CONNECTION FIX

Why this package is needed:
The live Ladies Ring category is showing 0 products because the current products.js has only the existing earrings and necklace product records. This replacement products.js merges 50 ring records from the supplied rings.pdf into the same catalogue data used by categories.html and product.html.

UPLOAD STEPS (GitHub mobile):
1. Extract this ZIP on your phone.
2. Open your GitHub repository: anshv87009-maker/jawaria-jewellers-site
3. Upload BOTH files in this folder to the repository root:
   - products.js (replace the existing file)
   - product.html (replace the existing file)
4. Commit the changes.
5. Wait a few minutes, then open:
   https://anshv87009-maker.github.io/jawaria-jewellers-site/categories.html?category=Ladies%20Ring
6. If it still shows 0 products, refresh in Chrome or open the link in an Incognito tab.

This fix does not need a separate rings.html page. The existing categories.html page will show the rings because they are now included in products.js. Clicking a ring opens product.html as usual.

Data notes:
- 50 ring records were added to the existing 98 records (54 earrings + 44 necklaces).
- Source specifications are shown where present in the prepared ring data.
- Estimated weights are explicitly labelled as estimates, not verified measurements. Confirm product details with the showroom before sale.
