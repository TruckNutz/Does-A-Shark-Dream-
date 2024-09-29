<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" href="style.css">
  <title>Where Does a Shark Dream?</title>
</head>
<body>
    <div class="container">
      <h1>WHERE DOES A SHARK DREAM</h1>
      <h2>Upon what doth a shark rest his eyes upon?</h2>
      <p>His Next Meal</p>
      <h2>Upon what doth a shark rest his fins upon?</h2>
      <p>His Place to Rest</p>
      <h2>Upon what doth a shark rest his love upon?</h2>
      <p>The Tallest Point of them all</p>
      <h2>Upon what doth a shark rest his story upon?</h2>
      <p>A book</p>
      <h2>Upon what doth a shark rest his home upon?</h2> 
      <p>His Love</p>
    </div>
    <div class="puzzle-container">
        <h1>Who Shall I Go to?</h1>
        <input type="text" id="puzzleAnswer" placeholder="Your answer here">
        <button onclick="checkAnswer()">Submit</button>
    </div>
    <script>
        function checkAnswer() {
            const answer = document.getElementById('puzzleAnswer').value.toLowerCase();
            if (answer === "burger") {
                alert("Fintastic! I want to return to him. Key: My adoption date");
            } else {
                alert("Nice Fin-tasy, try again");
            }
        }
    </script>
</body>
</html>
