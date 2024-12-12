---
title: YouTube Video Downloader For Free
---
-﻿--
l﻿ayout: post
-﻿--
<!DOCTYPE html>

<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Video Downloader</title>
  <style>
    body {
    font-family: Arial, sans-serif;
    background-color: #f0f0f0;
}

.container {
    max-width: 400px;
    margin: 40px auto;
    padding: 20px;
    background-color: #fff;
    border: 1px solid #ddd;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

.logo {
    font-size: 36px;
    font-weight: bold;
    margin-bottom: 10px;
}

h1 {
    text-align: center;
    margin-bottom: 20px;
}

form {
    margin-bottom: 20px;
}

input\[type="text"] {
    width: 100%;
    height: 40px;
    margin-bottom: 20px;
    padding: 10px;
    border: 1px solid #ccc;
}

button {
    width: 100%;
    height: 40px;
    background-color: #4CAF50;
    color: #fff;
    padding: 10px;
    border: none;
    border-radius: 5px;
    cursor: pointer;
}

button:hover {
    background-color: #3e8e41;
}

\#download-status {
    margin-top: 20px;
    font-size: 18px;
    font-weight: bold;
    color: #666;
}
  </style>

</head>

<body>
  <div class="container">
    <div class="logo">
      <span style="color: #FF69B4;">V</span>
      <span style="color: #33CC33;">i</span>
      <span style="color: #6666CC;">d</span>
      <span style="color: #FF9900;">e</span>
      <span style="color: #CC33CC;">o</span>
      <span style="color: #33CCCC;">D</span>
      <span style="color: #FF69B4;">o</span>
      <span style="color: #33CC33;">w</span>
      <span style="color: #6666CC;">n</span>
      <span style="color: #FF9900;">l</span>
      <span style="color: #CC33CC;">o</span>
      <span style="color: #33CCCC;">a</span>
      <span style="color: #FF69B4;">d</span>
      <span style="color: #33CC33;">e</span>
      <span style="color: #6666CC;">r</span>
    </div>
    <h1>Video Downloader</h1>
    <form>
      <input type="text" id="video-url" placeholder="Enter video URL">
      <button id="download-button">Download</button>
    </form>
    <div id="download-status"></div>
  </div>

  <script>
   const videoUrlInput = document.getElementById('video-url');
const downloadButton = document.getElementById('download-button');
const downloadStatus = document.getElementById('download-status');

downloadButton.addEventListener('click', (e) => {
    e.preventDefault();
    const videoUrl = videoUrlInput.value.trim();
    if (videoUrl) {
        downloadVideo(videoUrl);
    }
});

function downloadVideo(videoUrl) {
    // TO DO: implement video downloading logic here
    // For now, just display a success message
    downloadStatus.innerText = 'Video downloaded successfully!';
    downloadStatus.style.color = 'green';
}
  </script>

</body>

</html>