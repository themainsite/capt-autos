CAPT AUTOS WEBSITE UPDATE

Files:
- index.html
- inventory.html
- sell-swap.html
- history.html
- admin.html
- capt-autos-logo.PNG
- setup-post-multiple-photos.sql

IMPORTANT:
1. Run setup-post-multiple-photos.sql in Supabase SQL Editor. Paste only the SQL code.
2. Replace the five HTML files in the GitHub repository root with the files in this package.
3. Keep capt-autos-logo.PNG in the repository root.
4. Commit changes to the main branch and allow GitHub Pages to redeploy.

Changes:
- Replaced arrow-style emoji/symbol indicators with consistent inline interface icons.
- Added multiple photo uploads to admin website posts (up to 10 images, JPG/PNG/WebP, max 5 MB each).
- Existing single-image posts are migrated into the new image_urls array.
- Visitors can tap a post photo on the homepage to open a gallery showing every attached photo.
- Admin post cards show all attached photos.

No changes to the existing car inventory, customer request, history-token or authentication workflows.
