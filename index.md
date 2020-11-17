## Welcome to GitHub Pages

<script src="https://cdn.jsdelivr.net/npm/hls.js@latest"></script>
<link rel="stylesheet" href="./js/DPlayer.min.css">
<script src="./js/DPlayer.min.js"></script>

<div id="dplayer"></div>
<script>
const dp = new DPlayer({
    container: document.getElementById('dplayer'),
    screenshot: true,
    video: {
        url: './5.mp4',
        pic: 'demo.jpg',
        thumbnails: 'thumbnails.jpg',
    },
    subtitle: {
        url: 'webvtt.vtt',
    },
    danmaku: {
        id: 'demo',
        api: 'https://api.prprpr.me/dplayer/',
    },
});
</script>



<video width="658" height="444" preload="none" controls="controls"><source src="/5.mp4" /></video>
