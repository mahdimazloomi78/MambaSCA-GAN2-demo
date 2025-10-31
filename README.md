# Audio Demo Site Template (GitHub Pages)

This repository provides a boilerplate template for building a simple website for audio demos, suitable for research projects (e.g., similar to the ReSepNet demo pages). It is designed to work both **online** when deployed to GitHub Pages and **offline** by simply opening the `index.html` file in a local browser.

## 1) Adding Your Files
- Copy your audio files (WAV/MP3) into the `audio/` directory.
- Place your spectrogram images (or any other images, PNG/JPG) into the `img/` directory.
- Update the `index.html` file to point to your new file paths and names.

## 2) Offline Testing
Open the `index.html` file directly in your browser from your local machine to test everything. If audio files do not play, double-check the file paths in the HTML and ensure they correctly reference the files in the `audio/` directory.

## 3) Deploying to GitHub Pages (Free)
1.  Create a GitHub account and sign in.
2.  Create a new repository (e.g., `speech-demo`).
3.  Upload the contents of this template folder to your new repository (using the `Add file` > `Upload files` button, or via Git).
4.  In your repository's settings, go to **Settings > Pages**. In the **Build and deployment** section, set the **Source** to **Deploy from a branch**. Select the **main** branch (or `master`) and the **/(root)** folder. Click **Save**.
5.  After a few moments, your site will be live at `https://USERNAME.github.io/REPOSITORY_NAME/`.

> Official Documentation: GitHub Pages - GitHub Docs: [https://docs.github.com/en/pages](https://docs.github.com/en/pages)

## Notes
- This method is for creating a **Project Site**, which is hosted at an address like `USERNAME.github.io/REPOSITORY_NAME/`.
- If you want a **User Site** (a single site hosted at `USERNAME.github.io`), you must create a repository named exactly `USERNAME.github.io`.
- You can add a custom domain later via **Settings > Pages > Custom domain**.
