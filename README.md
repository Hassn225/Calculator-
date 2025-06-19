<html>
<head>
  <title>Combined Array Example</title>
</head>
<body>

  <h2>Simple Array with ID and Name</h2>
  <p id="userOutput"></p>

  <h2>JavaScript Fruits Array</h2>
  <p id="fruitsOutput"></p>

  <script>
    // --- User Array ---
    let user = [
      ["1", "Ali"],
      ["2", "Hamza"],
      ["3", "Safiq"],
      ["4", "Kodu"]
    ];
    document.getElementById("userOutput").innerHTML = "ID: " + user[0][0] + ", Name: " + user[0][1];
    console.log("User Array:", user);

    // --- Fruits Array ---
    let fruits = ["Apple", "Banana", "Mango", "Orange"];
    document.getElementById("fruitsOutput").innerHTML = "Fruits: " + fruits.join(", ");
    console.log("Fruits Array:", fruits);
  </script>

</body>
</html>