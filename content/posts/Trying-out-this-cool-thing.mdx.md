---
title: Trying out this cool thing
---


```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Animated ASCII Text</title>
  <style>
    body {
      background-color: #000;
      color: #0f0;
      font-family: monospace;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      margin: 0;
    }

    .ascii-art {
      white-space: pre;
      text-align: center;
      animation: color-change 5s infinite;
    }

    @keyframes color-change {
      0% {
        color: #0f0;
      }

      25% {
        color: #f00;
      }

      50% {
        color: #00f;
      }

      75% {
        color: #ff0;
      }

      100% {
        color: #0f0;
      }
    }
  </style>
</head>

<body>
  <div class="ascii-art">
    <pre>

 _____ ______   ___  ___  ___  ___  _________  ________  ________  ___  _____ ______      
|\   _ \  _   \|\  \|\  \|\  \|\  \|\___   ___\\   __  \|\   ____\|\  \|\   _ \  _   \    
\ \  \\\__\ \  \ \  \\\  \ \  \\\  \|___ \  \_\ \  \|\  \ \  \___|\ \  \ \  \\\__\ \  \   
 \ \  \\|__| \  \ \  \\\  \ \   __  \   \ \  \ \ \   __  \ \_____  \ \  \ \  \\|__| \  \  
  \ \  \    \ \  \ \  \\\  \ \  \ \  \   \ \  \ \ \  \ \  \|____|\  \ \  \ \  \    \ \  \ 
   \ \__\    \ \__\ \_______\ \__\ \__\   \ \__\ \ \__\ \__\____\_\  \ \__\ \__\    \ \__\
    \|__|     \|__|\|_______|\|__|\|__|    \|__|  \|__|\|__|\_________\|__|\|__|     \|__|
                                                           \|_________|
        </pre>
  </div>
</body>

</html>
```
