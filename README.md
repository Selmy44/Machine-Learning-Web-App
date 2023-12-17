<!DOCTYPE html>
<html>
<head>
  <title>Machine Learning Web App</title>
  <style>
    /* Inline CSS */
    body {
      font-family: Arial, sans-serif;
      text-align: center;
      margin-top: 50px;
    }
    .input-container {
      margin-bottom: 20px;
    }
    button {
      padding: 10px 20px;
      font-size: 16px;
      cursor: pointer;
    }
    #result {
      font-weight: bold;
      margin-top: 20px;
    }
  </style>
</head>
<body>
  <h1>Machine Learning Web App</h1>
  
  <div class="input-container">
    <label for="inputData">Enter Data:</label>
    <input type="text" id="inputData" placeholder="Type something...">
  </div>
  
  <button onclick="performMachineLearning()">Submit</button>
  
  <div id="result"></div>

  <script>
    // Inline JavaScript
    function performMachineLearning() {
      // This is where you might implement your machine learning functionality
      // For the sake of this example, let's just display the input data
      const inputData = document.getElementById('inputData').value;
      document.getElementById('result').innerText = `Input Data: ${inputData}`;
    }
  </script>
</body>
</html>
