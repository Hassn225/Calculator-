<!DOCTYPE html>
<html>
<head>
  <title>Mapping Odd and All Numbers</title>
</head>
<body>

  <h2>Original Array of 20 Numbers</h2>
  <p id="numbersOutput"></p>

  <h2>Odd Numbers Only (Filtered)</h2>
  <p id="oddNumbersOutput"></p>

  <h2>Mapped: Odd Numbers × 4 (Others Unchanged)</h2>
  <p id="mappedOddOutput"></p>

  <h2>Mapped: All Numbers × 2</h2>
  <p id="mappedDoubleOutput"></p>

  <script>
    // Original array
    let numbers = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10,
                   11, 12, 13, 14, 15, 16, 17, 18, 19, 20];

    // Filter odd numbers
    let oddNumbers = numbers.filter(num => num % 2 !== 0);

    // Map: multiply odd numbers by 4, leave even numbers unchanged
    let mappedOdd = numbers.map(num => (num % 2 !== 0 ? num * 4 : num));

    // Map: multiply all numbers by 2
    let mappedDouble = numbers.map(num => num * 2);

    // Display results
    document.getElementById("numbersOutput").innerHTML = "Original Numbers: " + numbers.join(", ");
    document.getElementById("oddNumbersOutput").innerHTML = "Odd Numbers: " + oddNumbers.join(", ");
    document.getElementById("mappedOddOutput").innerHTML = "Mapped (Odd × 4): " + mappedOdd.join(", ");
    document.getElementById("mappedDoubleOutput").innerHTML = "Mapped (All × 2): " + mappedDouble.join(", ");

    // Console logs
    console.log("Original Numbers:", numbers);
    console.log("Odd Numbers:", oddNumbers);
    console.log("Mapped (Odd × 4):", mappedOdd);
    console.log("Mapped (All × 2):", mappedDouble);
  </script>

</body>
</html>