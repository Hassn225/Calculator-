<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Responsive Layout (Plain CSS)</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #fff;
      padding: 40px;
    }

    .container {
      max-width: 60%;
      margin: 0 auto;
      border: 1px solid #ccc;
      padding: 30px;
    }

    h2 {
      margin-bottom: 20px;
    }

    p {
      margin-bottom: 30px;
    }

    .column {
      border: 1px solid #ccc;
      padding: 10px;
      text-align: center;
      margin: 20px;
      width: 100%;
      gap: 0px;
    }

    .button-wrapper {
      text-align: center;
      margin-top: 20px;
    }

    button {
      padding: 10px 20px;
      background-color: royalblue;
      color: white;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }

    .alert {
      background-color: #fff3cd;
      color: #856404;
      padding: 15px;
      margin-top: 20px;
      border-radius: 5px;
      border: 1px solid #ffeeba;
    }
  </style>
</head>
<body>

  <div class="container">
    <h2>Responsive Layout</h2>
    <p>
      This is a simple hero unit, a simple jumbotron-style component, for calling
      extra attention to featured content or information.
    </p>

    <div class="column">Column</div>
    <div class="column">Column</div>
    <div class="column">Column</div>

    <div class="button-wrapper">
      <button>Button</button>
    </div>

    <div class="alert">
      This is an alert—check it out!
    </div>
  </div>

</body>
</html>