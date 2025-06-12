<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Card and Boxes (Plain CSS)</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      padding: 100px;
      background-color: #f4f4f4;
    }

    .card {
      background-color: white;
      border: 1px solid #ccc;
      padding: 20px;
      margin-bottom: 30px;
      width: 100%;
    }

    .card-title {
      font-size: 20px;
      font-weight: bold;
      margin-bottom: 10px;
    }

    .boxes {
      display: flex;
      gap: 20px;
    }

    .box {
      background-color: olive;
      color: white;
      padding: 20px;
      text-align: center;
      width: 80%;
    }
  </style>
</head>
<body>

  <div class="card">
    <div class="card-title">Card Title</div>
    <p>This is a card with padding, margin, and border.</p>
  </div>

  <div class="boxes">
    <div class="box">BOX 1</div>
    <div class="box">BOX 2</div>
    <div class="box">BOX 3</div>
  </div>

</body>
</html>