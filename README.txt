StockNest browser-only accounts with password recovery

This version does not use any online account service. It stores account information and each account inventory in the browser. Accounts only work on the same browser and device; they do not sync across devices. Clearing browser data can remove accounts and inventory.

Upload index.html, styles.css, and app.js together to the same GitHub Pages folder. Register a username (3-20 letters, digits, or underscores), password (at least 6 characters), and recovery question/answer. Forgot Password verifies that answer and lets the user choose a new password. Existing accounts without a recovery question can add one under Edit profile before resetting.

On the Products page, Edit opens a popup dialog with the selected product details. Save changes to apply them, or cancel/press Escape to leave the product unchanged.

Recovery answers and password verification values are stored locally. This is suitable for a classroom or demo app, not secure multi-user production authentication; someone with access to the browser can inspect or change local data.
