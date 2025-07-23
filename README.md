<!DOCTYPE html>
<html>
<head>
    <title>Video</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            background: #000;
            overflow: hidden;
        }
        video {
            width: 100%;
            height: 100vh;
            object-fit: cover;
        }
    </style>
</head>
<body>
    <video autoplay muted loop playsinline>
        <source src="your-video.mp4" type="video/mp4">
    </video>
</body>
</html>
