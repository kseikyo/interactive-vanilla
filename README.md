# CStories

To run this project, install the dependencies with your preferred package manager.

## Dev mode
```bash
# in 2 different terminals run
npm run assets

npm run dev
```

- npm run assets
    this will serve the assets using the http-server package at localhost:8081
- npm run dev
    this will make the project available on localhost:8080

---
The current architecture uses a manifest.json to handle all the data that will be used in the video, the goal of the project is to make it scalable by using databases and hosting the videos in a CDN.