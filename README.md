<html>
<head>
  <title>Current Date</title>
</head>
<body>

  <p id="date"></p>

  <script>
    // Get the current date and time
    var today = new Date();

    // Format the date as "MM/DD/YYYY" - changed to MM/DD
    var dateString = today.getMonth() + 1 + "/" + today.getDate();

    // Display the date in the HTML
    document.getElementById("date").innerHTML = dateString;
  </script>

</body>
</html>
