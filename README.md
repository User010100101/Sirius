<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>jid</title>
  <style>
    body {
      background-image: 
      url('https://i.postimg.cc/cJhZn8gP/Untitled5-20240103171343.png');
      background-size:cover;
      background-position:center;
      margin:0;
      padding:0;
    }
    h1 {
      color:chartreuse;
      letter-spacing: 2px
    }
    h2 {
      color:ghostwhite;
      letter-spacing: 5px
    }
    a {
      color:navajowhite;
      font-size:30px;
    }
  </style>
</head>
<body>
  <script>
    // Get the user's name
    var username = prompt("What's your name?");

    // Display a personalized message
    if (username !== null && username !== "jid") {
      alert("What do you need, " + username + "?");
    } else {
      // Display an image in the else block
      document.write("<img src='https://i.ibb.co/g9vs6qR/IMG-20231212-101317-156.jpg' alt='IMG-20231212-101317-156' style='width: 50%; height: auto; border: 22px solid darkbrown; margin: 25px; padding: 22px;'>");
      // Add a paragraph and a link under the image
      document.write("<h1>JADE VINCENT PACANZA</h1>" +
        "<h2><i>age:15 <br>" +
        "School :joyful angels academy<br>" +
       " gender:male<br>" +
       "species: human</i></h2>" +
      "<a href='https://www.facebook.com/profile.php?id=100083377539987'>JADE'S facebook</a>");
      // Prompt user and show response
      var response = prompt("JID'S INFO? (y/n)");
      alert("(click anywhere)");
    }
  </script>
  <script>
    // Change the URL without reloading the page
    history.pushState({}, null, 'jidtestpic.com');
  </script>
</body>

</html>
