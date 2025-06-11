<!DOCTYPE html>
<html>
<head>
  <title>Array of 20 Numbers</title>
</head>
<body>

  <h2>Array of 20 Numbers</h2>
  <p id="numbersOutput"></p>

  <script>
    // Create an array of 20 numbers (1 to 20)
    let numbers = [];
    for (let i = 1; i <= 20; i++) {
      numbers.push(i);
    }

    // Display the numbers in the browser
    document.getElementById("numbersOutput").innerHTML = "Numbers: " + numbers.join(", ");

    // Also log to console
    console.log("Array of 20 Numbers:", numbers);
  </script>

</body>
</html>