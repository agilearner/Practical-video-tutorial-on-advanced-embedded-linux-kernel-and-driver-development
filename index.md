<!DOCTYPE HTML>
<html lang="en-US">


  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width,initial-scale=1">
    <title>DPlayer</title>
	<script src="https://cdn.jsdelivr.net/npm/hls.js@latest"></script>
    <script src="https://cdn.jsdelivr.net/npm/dplayer/dist/DPlayer.min.js"></script>
  </head>
<body>
<div id="dplayer"></div>

<video playsinline="" webkit-playsinline="" preload="auto" controls="" src="https://pro-video.xiaoheiban.cn/ihu/206e4370-7f56-48c0-beff-17847687561a.mp4" width="100%"></video>


<script>
const dp = new DPlayer({
    container: document.getElementById('dplayer'),
    video: {
        url: 'https://cdn.jsdelivr.net/gh/agilearner/Practical-video-tutorial-on-advanced-embedded-linux-kernel-and-driver-development/gh-pages/1/1-1.m3u8',
        type: 'hls',
    },
    pluginOptions: {
        hls: {
            // hls config
        },
    },
});
</script>


</body>
</html>









