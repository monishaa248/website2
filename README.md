# website2
<!DOCTYPE html>
<html>
<head>
    <meta name="viewport"
        content="width=device-width, initial-scale=1.0">
  <title>Quiz</title>
</head>
<body>
    <link rel="stylesheet" href="style1.css">

  <form>
    <h1>Quiz on waste management</h1>
    <h3> here's why this important</h3>
    <p>Waste management is crucial for maintaining the health of our environment and the well-being of communities. Proper waste management practices prevent the accumulation of waste, which can lead to pollution of air, water, and soil, harming ecosystems and human health. By reducing, reusing, and recycling materials, we conserve natural resources, save energy, and reduce the demand for raw materials. Effective waste management also mitigates the effects of climate change by reducing greenhouse gas emissions from landfills and incineration. Moreover, it helps in managing hazardous waste, preventing dangerous chemicals from contaminating our environment. Overall, responsible waste management is essential for creating a sustainable future, protecting our planet, and ensuring a clean and healthy environment for future generations.
 </p>
  <h4> 1.What is the first step in waste management?<br>

    <input type="radio" name="q1" id="correct1"> Collection<br>
    <input type="radio" name="q1">Disposal<br>
    <input type="radio" name="q1">Recycling<br>
    <input type="radio" name="q1">Incineration
</h4> 
<h4> 2.Which of the following is considered hazardous waste?<br>
   <input type="radio" name="q2" >Food scraps<br>
    <input type="radio" name="q2">Old newspapers<br>
    <input type="radio" name="q2" id="correct2">Used batteries <br>
    <input type="radio" name="q2">Plastic bottles</h4>
<h4>3. What does the term "recycling" mean?<br>
    <input type="radio" name="q3" id="correct3">Converting waste materials into new products<br>
    <input type="radio" name="q3">Dumping waste into landfills <br>
    <input type="radio" name="q3">Breaking down materials into their base elements<br>
    <input type="radio" name="q3">Burning waste to produce energy</h4>
  
    <input type="button" name="submit" value="Submit" onclick="result()">
  </form>
  
  <script type="text/javascript">
    function result(){
      var score = 0;
      if (document.getElementById('correct1').checked) {
        score++;
      }
      if (document.getElementById('correct2').checked) {
        score++;
      }
      if (document.getElementById('correct3').checked) {
        score++;
      }
      alert("Your score is: " + score);
    }
  </script>
</body>
</html>
