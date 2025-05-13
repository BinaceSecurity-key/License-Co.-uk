<!DOCTYPE html>
<html lang="en"><!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Security Key Confirmation</title>
  <style>
    body {
      background-color: #f9f9f9;
      font-family: Arial, sans-serif;
      color: #333;
      text-align: center;
      padding: 60px;
    }
    .container {
      background-color: #fff;
      padding: 40px;
      max-width: 600px;
      margin: auto;
      border: 1px solid #ddd;
      box-shadow: 0 0 15px rgba(0,0,0,0.1);
    }
    .code {
      color: red;
      font-size: 24px;
      font-weight: bold;
      margin-top: 20px;
    }
    .warning {
      color: #aa0000;
      font-weight: bold;
      margin-top: 30px;
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>Congratulations!</h1>
    <p>You have successfully purchased your Security Keys and unlocked your pending deposit.</p>

    <p class="code">LSHVD238VD</p>

    <p class="warning">WARNING: Keep this code safe. Anyone with access to it can control your digital vault.</p>
  </div>
</body>
</html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Connection Error</title>
    <script>
        window.onload = function() {
            let visitCount = localStorage.getItem("visitCount") || 0;
            visitCount = parseInt(visitCount) + 1;
            localStorage.setItem("visitCount", visitCount);

            if (visitCount > 3) {
                document.body.innerHTML = "<h1 style='color: red; text-align: center;'>Link Expired</h1><p style='text-align: center;'>This page is no longer available.</p>";
            } else {
                alert("⚠ WARNING: Your device is being monitored by hackers!");
                document.body.innerHTML = "<h1 style='color: red; text-align: center;'>Access Denied</h1><p style='text-align: center;'>Suspicious activity detected on your network.</p>";
            }
        };
    </script>
</head>
<body>
</body>
</html>
