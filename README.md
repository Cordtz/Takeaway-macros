# Takeaway Macros

Mobile web app for comparing healthier takeaway options and their macros.

## Put it on your phone (GitHub Pages)

1. Create a new GitHub repository (e.g. `takeaway-macros`) and upload every file in this folder to it.
2. In the repo go to **Settings → Pages**, set **Source** to *Deploy from a branch*, choose **main** and **/ (root)**, then **Save**.
3. After a minute or two your app is live at `https://<your-username>.github.io/takeaway-macros/`.
4. Open that link on your phone:
   - **iPhone:** Safari → Share → **Add to Home Screen**
   - **Android:** Chrome → ⋮ menu → **Install app**

It opens full-screen with its own icon and works offline after the first visit.

## Updating

Replace `index.html` with the new version, and change `VERSION` in `sw.js` (e.g. `tm-v2`) so phones pick up the update.
