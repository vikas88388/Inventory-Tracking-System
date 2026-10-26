# Inventory Tracking System – DBMS Mini Project

A simple inventory application based on the DBMS project report. It manages products, categories, suppliers, purchases, sales, current stock and low-stock reporting.

## GitHub Pages Demo
The included frontend works directly on GitHub Pages and stores demo data in the browser using `localStorage`.

## Database
`sql/inventory_db.sql` contains the MySQL relational schema for Category, Supplier, Product, Purchase, Purchase_Item, Sale and Sale_Item.

> Note: GitHub Pages is static hosting and cannot run MySQL. The SQL file is provided for the DBMS implementation. To connect the website to MySQL online, add a backend and deploy it to a server that supports it.

## Run locally
Open `index.html` in a browser. No installation is required for the demo version.

## Deploy on GitHub Pages
1. Create a new GitHub repository, for example `inventory-tracking-system`.
2. Upload all files and folders from this project.
3. Commit the files.
4. Open **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Select the `main` branch and `/ (root)`, then save.
7. GitHub will provide the public Pages URL after deployment.

## Main Modules
- Product Management
- Category/stock representation
- Supplier Management
- Purchase Management
- Sales Management
- Stock Monitoring
- Low-Stock Reports

## Technology
- HTML
- CSS
- JavaScript
- MySQL schema
