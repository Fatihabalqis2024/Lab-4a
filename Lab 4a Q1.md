# Lab-4a
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Change Paragraph Content</title>
</head>
<body>

<div id="myElement">
  <p>Welcome to my website!</p>
</div>

<button onclick="changeContent()">Change Content</button>

<script>
  function changeContent() {
    document.querySelector("#myElement p").innerText = "Hello there!";
  }
</script>

</body>
</html>