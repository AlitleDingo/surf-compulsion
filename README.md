# Surf Compulsion

A surf video showcase website published with GitHub Pages.

## Add your video
The player expects this file:

```text
videos/surf-video.mp4
```

Upload your own MP4 into the `videos` folder and name it `surf-video.mp4`. The folder has a README so it exists in the repository already. Once the file is committed, the site will use it automatically.

GitHub repositories have file size limits, and GitHub Pages is not intended as a large-video hosting service. For a large video, host it on a video platform or another file host and replace the `<source>` URL in `index.html` with a supported video URL or embed.

## Publish with GitHub Pages
The repository includes a GitHub Actions workflow at `.github/workflows/deploy-pages.yml`. In the repository, open **Settings → Pages** and select **GitHub Actions** as the build and deployment source. The workflow deploys on pushes to `main` and can also be started manually from the Actions tab.

After deployment, the site URL should be:

```text
https://alitledingo.github.io/surf-compulsion/
```
