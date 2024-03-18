<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Marriage Proposal</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #fce4ec; /* Light pink background */
    }
    .dialog-container {
      position: absolute;
      top: 50%;
      left: 50%;
      transform: translate(-50%, -50%);
      text-align: center;
    }
    .dialog-box {
      background-color: #fff;
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.3);
    }
    .button-container {
      position: fixed;
      bottom: 20px;
      right: 20px;
    }
    .button {
      display: block;
      width: 120px;
      padding: 10px;
      margin-bottom: 10px;
      text-align: center;
      border-radius: 5px;
      background-color: #ffb6c1; /* Light pink button background */
      color: #fff;
      text-decoration: none;
      font-weight: bold;
      box-shadow: 0 2px 4px rgba(0, 0, 0, 0.2);
    }
    .button:hover {
      background-color: #ff69b4; /* Lighter pink on hover */
    }
  </style>
</head>
<body>

<div class="dialog-container">
  <div class="dialog-box">
    <h1>Will you MARRY me?</h1>
    <div class="button-container">
      <a href="#" class="button" onclick="showLove('Yes')">Yes</a>
      <a href="#" class="button" onclick="showLove('Definitely Yes')">Definitely Yes</a>
    </div>
  </div>
</div>

<script>
  function showLove(response) {
    alert("Alhamdulillah, I love you so much!!");
  }
</script>

</body>
</html>
