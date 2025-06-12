<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Card and Boxes</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
  <style>
    .box {
      background-color: olive;
      color: white;
      padding: 20px;
      text-align: center;
      margin: 10px;
    }
  </style>
</head>
<body>

  <div class="container mt-5">
    <!-- Card -->
    <div class="card mb-4">
      <div class="card-body">
        <h5 class="card-title">Card Title</h5>
        <p class="card-text">This is a card with padding, margin, and border.</p>
      </div>
    </div>

    <!-- Boxes -->
    <div class="d-flex justify-content-between">
      <div class="box">BOX 1</div>
      <div class="box">BOX 2</div>
      <div class="box">BOX 3</div>
    </div>
  </div>

</body>
</html>