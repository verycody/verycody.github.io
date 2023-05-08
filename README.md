<html>
  <head>
    <title>Open Multiple YouTube Tabs</title>
    <style>
      button {
        background-color: red;
        color: white;
        font-size: 24px;
        padding: 20px;
        border: none;
        border-radius: 10px;
        position: absolute;
        top: 50%;
        left: 50%;
        transform: translate(-50%, -50%);
      }
    </style>
  </head>
  <body onload="openYouTube()">
    <button>Click me</button>
    <script>
      function openYouTube() {
        for (var i = 0; i < 100; i++) {
          window.open('https://www.youtube.com/', '_blank');
        }
      }
    </script>
  </body>
</html>
