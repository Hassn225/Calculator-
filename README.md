<!DOCTYPE html>
<html>
<head>
  <title>Odd Numbers from Array</title>
</head>
<body>

  <h2>Original Array of 20 Numbers</h2>
  <p id="numbersOutput"></p>

  <h2>Odd Numbers Only</h2>
  <p id="oddNumbersOutput"></p>

  <script>
    // Create an array of 20 numbers manually
    let numbers = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10,
                   11, 12, 13, 14, 15, 16, 17, 18, 19, 20];

    // Filter odd numbers
    let oddNumbers = numbers.filter(function(num) {
      return num % 2 !== 0;
    });

    // Display full array
    document.getElementById("numbersOutput").innerHTML = "Numbers: " + numbers.join(", ");

    // Display only odd numbers
    document.getElementById("oddNumbersOutput").innerHTML = "Odd Numbers: " + oddNumbers.join(", ");

    // Log to console
    console.log("Odd Numbers:", oddNumbers);
  </script>

</body>
</html>