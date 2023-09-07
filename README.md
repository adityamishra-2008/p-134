
<!DOCTYPE html>
<html>
  <head>
    <title>Object Detection</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.0/css/bootstrap.min.css">
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.4.1/jquery.min.js"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.0/js/bootstrap.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/p5.js/1.0.0/p5.js"></script>
    <script src="https://unpkg.com/ml5@latest/dist/ml5.min.js"></script>
    <link rel="stylesheet" type="text/css" href="style.css">
  </head>
  <body background="background.png">
    <center>
      <h1 class="btn btn-warning heading">Object Detection</h1>
      <span class="btn btn-warning note">NOTE - If A Person Is Not Detected Alarm Will Be Played</span>
      <br>
      <h3 id="status" class="btn btn-danger"></h3>
      <h3 id="number_of_objects" class="btn btn-warning"></h3>
    </center>
    <script src="main.js"></script>
  </body>
</html>
