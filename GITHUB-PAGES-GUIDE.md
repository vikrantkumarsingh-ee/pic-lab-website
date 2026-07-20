# Publish the PIC Lab website with GitHub Pages

These steps require only a web browser. No command line or Git installation is needed.

## 1. Create a GitHub account

1. Visit GitHub and choose **Sign up**.
2. Choose a professional username. The username will appear in the first website address.
3. Verify your email and sign in.

## 2. Create a repository

1. Select the **+** menu in the upper-right corner.
2. Choose **New repository**.
3. Name the repository `pic-lab-website`.
4. Choose **Public**.
5. Leave “Add a README” unchecked because this package already contains one.
6. Select **Create repository**.

## 3. Upload the website

1. Extract the ZIP package on your computer.
2. Open the extracted folder.
3. In the empty GitHub repository, choose **Add file → Upload files**.
4. Drag all files and folders from inside the extracted folder into the upload area.
5. Confirm that `index.html` will appear at the repository root, not inside an extra folder.
6. Enter the message `Add PIC Lab website version 1`.
7. Select **Commit changes**.

The included videos have been compressed to browser-compatible H.264 files and are small enough for browser upload.

## 4. Enable GitHub Pages

1. Open the repository **Settings**.
2. Select **Pages** in the left sidebar.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select branch `main` and folder `/(root)`.
5. Select **Save**.

The initial address will usually be:

`https://YOUR-USERNAME.github.io/pic-lab-website/`

Publication may take several minutes.

## 5. Enable HTTPS

Return to **Settings → Pages** and enable **Enforce HTTPS** when available.

## 6. Update the website later

1. Open the repository.
2. Open the file to change.
3. Select the pencil icon to edit text, or use **Add file → Upload files** to replace images or videos.
4. Commit the change.
5. GitHub Pages will republish automatically.

## Important future update

After the public GitHub Pages address is known, a sitemap with absolute URLs can be added. A sitemap is not required for the first launch.

## Large future videos

For future videos larger than GitHub’s browser-upload limit, compress them first or host them on an approved video platform and embed them.
