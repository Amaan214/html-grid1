# html-grid1<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Mondrian Project</title>
  <style>
   
    .container{
      background: #dee0d9;
      height: 748px;
      width: 748px;
      display: grid;
      grid-template-rows: 1fr 1fr 1fr 1fr;
      grid-template-columns: 1fr 1fr 1fr 1fr;
    }
    .Red{
    background:#E72F24 ;
    height: 414px;
    width: 320px;
    border-bottom: 9px solid;
    border-right: 9px solid;
    }
    .Black{
    background:#232629 ;
    height: 20px;
    width: 153px;
    border-top: 9px solid;
    border-left: 9px solid;
    }
    .Blue{
    background:#004592;
    height: 130px;
    width: 50px;
    border-bottom: 15px solid;
    border-top: 9px solid;
    border-left: 9px solid;
    }
    .Yellow{
    background:#F9D01E ;
    height: 20px;
    width: 198px;
    border-bottom: 9px solid;
    }
    .White1{
      display: grid;
      grid-column: span 3;
      border-bottom: 9px solid;
    }
    .White2{
      display: grid;
      grid-row: span 3;
      border-bottom: 9px solid;
      border-right: 9px solid;
    }
    .White3{
      display: grid;
      grid-area: 2 / 2 /4 /4 ;
      border-right: 9px solid;
      border-bottom: 9px solid;
      grid-row: span 3;
    }
    .Blue{
      display: grid;
    }
    .White4{
      display: grid;
      grid-row: span 2;
    }
    body{
      display: flex;
      justify-content: center;
      align-items: center;
      margin: 0;
    }
    .White5{
      border-right: 9px solid;
    }
  </style>
</head>

<body>
  <!-- Write your HTML here -->
  <div class="container">
    <div class="Red"></div>
    <div class="White1"></div>
    <div class="White2"></div>
    <div class="White3"></div>

    <div class="Blue"></div>
    <div class="White4"></div>
    
    <div class="White5"></div>
    <div class="Yellow"></div>
    <div class="Black"></div>
  </div>
</body>

</html>
