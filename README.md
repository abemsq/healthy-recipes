# Static Website: Wine Festival Schedule

Simple static website introducing quinoa salad recipe

![image](https://github.com/abemsq/healthy-recipes/blob/master/picture.png)

## HTML
```
<!DOCTYPE html>
<html>

<head>
  <title>Quinoa and Kale Salad Recipe</title>
  <link href="style.css" type="text/css" rel="stylesheet">
</head>

<body>

  <img src="https://s3.amazonaws.com/codecademy-content/courses/freelance-1/unit-2/salad.jpg" alt="Kale Caeasar Salad"/>
  <h1>Kale Caesar Quinoa Salad with Roasted Chicken</h1>
  <p class="description">Kale and quinoa provide a healthy base for roasted chicken topped with a light Caesar sauce.</p>

  <p id="cook-time">Total time: 45 minutes</p>

  <h2>Ingredients</h2>
  <ul class="ingredients">
    <li>1/4 cup kale</li>
    <li>1 cup Quinoa</li>
    <li>2 tbsp Olive Oil</li>
    <li>1 chicken breast</li>
    <li>Caesar Dressing</li>
  </ul>

  <h2>Preparation</h2>
  <ol>
    <li>
      <p>Prepare quinoa and roast chicken until golden brown and 165 in middle.</p>
      <p class="time">Time: 40 minutes</p>
    </li>
    <li>
      <p>Toss quinoa, chicken, kale, and Caesar dressing until coated.</p>
      <p class="time">Time: 4 minutes</p>
    </li>
    <li>
      <p>Add walnuts and olive oil as garnish.</p>
      <p class="time">Time: 1 minute</p>
    </li>
  </ol>

  <p class="citation">Find this recipe and more <a href="http://www.myrecipes.com/recipe/kale-caesar-salad-chicken" target="_blank" class="external-link">here</a>.</p>

</body>

</html>
```

## CSS

```
body {
    background-color: #242f44;
    color: white;
      font-family: 'Oswald', sans-serif;
  }
  
  header {
    text-align: center;
    margin-top: 5px;
  }
  
  h1 {
    font-size: 36px;
    padding: 15px;
    color: #8c6b48;
    background-color: white;
  }
  
  h2 {
    font-size: 24px;
    padding: 15px;
    text-transform: uppercase;
  }
  
  h3 {
    font-size: 20px;
    padding: 15px;
    text-transform: uppercase;
    text-align: left;
    margin-left: 20px;
    font-weight: 500;
    line-height: 2.7;
    letter-spacing: 0.8px;
  }
  
  th {
    border: 2px solid #8c6b48;
  }
  
  table {
    text-align: center;
    margin: 20px auto;
  }
  
  td {
    border: 2px solid #8c6b48;
    width: 300px;
  }
  
  footer {
    margin-top: 50px;
    text-align: center;
    position: fixed;
    width: 100%;
    bottom: 5px;
    background-color: #242f44;
    z-index: 5;
  }
  footer h3 {
    display: inline-block;
    font-size: 14px;
    background-color: #242f44;
  }
  
  .container {
    max-width: 940px;
    margin: 0 auto;
    height: 800px;
  }
  
  
  .left {
    width: 150px;
  }
```
