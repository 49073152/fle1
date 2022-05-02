# flex1
<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Flex</title>
</head>
<style>
  .flex-container {
    padding: 0;
    margin: 0;
    border: 10px;
    list-style: none;
    border: 10px solid rgb(192, 192, 192);
    -ms-box-orient: horizontal;
    display: -webkit-box;
    display: -moz-box;
    display: -ms-flexbox;
    display: -moz-flex;
    display: -webkit-flex;
    display: flex;
    justify-content: space-around;
  }
  
  .nowrap  { 
    -webkit-flex-wrap: nowrap;
    flex-wrap: nowrap;
    flex-direction: row;
  }
  
  .wrap    { 
    -webkit-flex-wrap: wrap;
    flex-wrap: wrap;
  }  
  .wrap li {
    background: tomato;
  }
  
  .wrap-reverse         { 
    -webkit-flex-wrap: wrap-reverse;
    flex-wrap: wrap-reverse;
    position: center;
  }  
  .wrap-reverse li {
    background: tomato;
    padding: 15px;
  }
  
  .flex-item {
    background: tomato;
    padding: 5px;
    width: 1500px;
    height: 100px;
    margin: 10px;
    list-style: none;
    
    line-height: 100px;
    color: black;
    font-weight: bold;
    font-size: 2em;
    text-align: left;
  }

  .flex-item1 {
    background: tomato;
    padding: 5px;
    width: 1500px;
    height: 100px;
    margin: 10px;
    list-style: none;
    
    line-height: 100px;
    color: black;
    font-weight: bold;
    font-size: 2em;
    text-align: center;
  }

  .flex-item2 {
    background: tomato;
    padding: 5px;
    width: 1500px;
    height: 100px;
    margin: 10px;

    line-height: 100px;
    color: black;
    font-weight: bold;
    font-size: 2em;
    text-align: center;
  }

  .flex-item3 {
    background: tomato;
    padding: 100px;
    width: 400px;
    height: 300px;
    margin: 10px;

    line-height: 100px;
    color: black;
    font-weight: bold;
    font-size: 2em;
    text-align: center;
  }

  .flex-item4 {
    background: tomato;
    padding: 5px;
    width: 500px;
    height: 300px;
    margin: 10px;

    line-height: 100px;
    color: black;
    font-weight: bold;
    font-size: 2em;
    text-align: center;
  }

  .flex-item5 {
    background: tomato;
    padding: 5px;
    width: 15000px;
    height: 100px;
    margin: 10px;

    line-height: 100px;
    color: black;
    font-weight: bold;
    font-size: 2em;
    text-align: center;
  }
</style>
<header>
    <ul class="flex-container nowrap">
      <li class="flex-item">logo</li>
    </ul>
</header>
  <body>
  <ul class="flex-container wrap">
    <li class="flex-item1">navigation</li>
  </ul>
  
  <ul class="flex-container wrap-reverse">
    <li class="flex-item2">header/baner</li>
  </ul>

  <ul class="flex-container wrap-reverse">
    <li class="flex-item3">sidebar</li>
    <li class="flex-item4">bodyarea</li>
  </ul>

  <ul class="flex-container wrap-reverse">
    <li class="flex-item5">footer</li>
  </ul>
</body>
</html>
