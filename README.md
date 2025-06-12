<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Bootstrap Layout Example</title>
  <!-- Bootstrap 5 CDN -->
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
  <style>
    .custom-box {
      background-color: olive;
      color: white;
      padding: 20px;
      text-align: center;
      margin: 10px;
      border-radius: 5px;
    }
  </style>
</head>
<body class="bg-light">

  <div class="container mt-5">

    <!-- Card Section -->
    <div class="card mb-4">
      <div class="card-body">
        <h5 class="card-title">Card Title</h5>
        <p class="card-text">This is a card with padding, margin, and border.</p>
      </div>
    </div>

    <!-- Boxes Section -->
    <div class="d-flex justify-content-between flex-wrap">
      <div class="custom-box flex-fill text-center mx-2">BOX 1</div>
      <div class="custom-box flex-fill text-center mx-2">BOX 2</div>
      <div class="custom-box flex-fill text-center mx-2">BOX 3</div>
    </div>

    <!-- Responsive Layout Section -->
    <div class="mt-5 p-4 border rounded bg-white">
      <h2>Responsive Layout</h2>
      <p>This is a simple hero unit, a simple jumbotron-style component, for calling extra attention to featured content or information.</p>

      <div class="row text-center">
        <div class="col-md-4 mb-3">
          <div class="p-3 border bg-light">Column</div>
        </div>
        <div class="col-md-4 mb-3">
          <div class="p-3 border bg-light">Column</div>
        </div>
        <div class="col-md-4 mb-3">
          <div class="p-3 border bg-light">Column</div>
        </div>
      </div>

      <button class="btn btn-primary mt-3">Button</button>

      <div class="alert alert-warning mt-3" role="alert">
        This is an alert—check it out!
      </div>
    </div>

  </div>

  <!-- Bootstrap JS -->
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>