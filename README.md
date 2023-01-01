# MADE FOR EDUCATIONAL PURPOSES ONLY!

### Full Stack Youtube to MP3 Converter that uses Next.JS.

How to run?
1) `npm i`
1) `npm run dev`

How to build?
1) `npm i`
2) `npm run build`

How to make a docker image?
1) `docker build -t mp3convert .` (MAKE SURE TO EXPOSE PORT 3000 WHILE RUNNING YOUR DOCKER IMAGE IN A CONTAINER!)

## General Info
1) The application tries to use [ffmpeg.wasm](https://github.com/ffmpegwasm/ffmpeg.wasm). If that doesn't work, it uses the backend server instead (endpoint: */api/download/stream*).
2) The application has been tested with **Node.JS Version 16.16.0** and it is working fine.
