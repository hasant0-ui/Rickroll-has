<!DOCTYPE html>
<html>
  <head>
    <style>
      body {
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        height: 100vh;
        margin: 0;
        text-align: center;
      }

      #yougotrickrolled, #note {
        opacity: 0;
        animation: fadeIn 3s 1.5s forwards; /* 1.5s delay */
      }

      #note {
        margin-top: 20px;
      }

      #rickroll {
        width: 600px;
        height: 400px;
        margin-top: 20px;
      }

      @keyframes fadeIn {
        to { opacity: 1; }
      }
    </style>
  </head>
  <body>
    <h2 id="yougotrickrolled">You got rickrolled!</h2>

    <p id="note">
      Note: This page was created as part of the Level 1 Computing course to test phishing awareness. Don’t worry, you’ve just been rickrolled!
    </p>

    <iframe id="rickroll"
      src="https://www.youtube.com/embed/dQw4w9WgXcQ"
      frameborder="0"
      allow="autoplay; encrypted-media"
      allowfullscreen>
    </iframe>
  </body>
</html>
