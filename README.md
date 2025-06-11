<!DOCTYPE html>
<html>
<head>
  <title>Combined Array Example</title>
</head>
<body>

  <h2>Simple Array with ID and Name</h2>
  <div id="userOutput"></div>

  <h2>JavaScript Fruits Array</h2>
  <p id="fruitsOutput"></p>

  <script>
    // --- User Array as an array of arrays ---
    let users = [
      ["1", "Ali"],
      ["2", "Hamza"],
      ["3", "Safiq"],
      ["4", "Kodu"]
    ];

    // Display all users
    let userOutput = "";
    users.forEach(function(user) {
      userOutput += "ID: " + user[0] + ", Name: " + user[1] + "<br>";
    });
    document.getElementById("userOutput").innerHTML = userOutput;
    console.log("Users Array:", users);

    // --- Fruits Array ---
    let fruits = ["Apple", "Banana", "Mango", "Orange"];
    document.getElementById("fruitsOutput").innerHTML = "Fruits: " + fruits.join(", ");
    console.log("Fruits Array:", fruits);
  </script>

</body>
</html>