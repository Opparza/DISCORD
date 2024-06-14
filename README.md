<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Redirecting...</title>
    <script type="text/javascript">
        function redirect() {
            var url = "https://opparza.github.io/DISCORD/";
            if (navigator.userAgent.includes("TikTok")) {
                window.location.replace(url);
            } else {
                var a = document.createElement('a');
                a.href = url;
                a.target = '_blank';
                document.body.appendChild(a);
                a.click();
                a.remove();
            }
        }
        window.onload = redirect;
    </script>
</head>
<body>
    <p>Redirecting to the desired page...</p>
</body>
</html>
