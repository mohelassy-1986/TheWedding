# Moustafa & Lina Wedding Guestbook

This package is already connected to the supplied Google Apps Script `/exec` URL.

## Google Apps Script

1. Open **Wedding Guestbook Backend** in Google Apps Script.
2. Replace the full contents of `Code.gs` with the supplied `Code.gs` file.
3. Save.
4. Select `setupGuestbook` and click **Run** once. Approve Drive and Sheets access if requested.
5. Go to **Deploy > Manage deployments**.
6. Edit the existing web-app deployment, choose **New version**, and deploy.
7. Keep **Execute as: Me** and access set to **Anyone**.

## GitHub Pages

1. Create a repository named `moustafa-lina-wedding-guestbook`.
2. Upload `index.html`, `README.md`, `.gitignore`, and optionally `Code.gs` to the repository root.
3. Commit to `main`.
4. Open **Settings > Pages**.
5. Choose **Deploy from a branch**, then `main` and `/(root)`.
6. Open the HTTPS Pages URL after publication.

## Test

1. The site status should show **Connected to Google Drive**.
2. Submit a text wish and check the `Wedding Guestbook Data` sheet.
3. Submit a photo, signature, and short voice wish and check the corresponding Drive folders.
4. Open the Pages URL on a second phone and click **Sync**.

Uploaded media is configured as **Anyone with the link can view**, so it can render in the shared guestbook. The root Drive folder itself is not made public by this code.
