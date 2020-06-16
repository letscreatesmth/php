<?php

// php class and function with js
// go down!  

/* 

               !! ATTENTION !!
   wait for all CDNs and functions to load.
             .: create by sami :.
*/
class js
{
  public $time;
  public function timer($time)
  {
     echo "setInterval(timer,1000);";
     echo "var x ="."$time".";";
     echo "function timer(){";
     echo "document.getElementById(\"demo\").innerHTML ='time: '+x;";
     echo "x--;";
         echo "if(x < 0){";
     echo "document.getElementById(\"demo\").innerHTML =\"Finished! :)\";";
     echo "clearInterval(timer);}}";
  }
}
function timer($time)
{
$text = new js();

$text -> timer("$time"); 
}

?>
<!doctype html>
<html>
<head>
  <link href="https://fonts.googleapis.com/css2?family=Sriracha&display=swap" rel="stylesheet">
  <style>
    body
    {
      font-family: 'Sriracha', cursive;
      margin: 0;
      padding: 0;
      background-color: #204051;
    }
    .box{
      border: solid #127681 5px;
      width: 300px;
      height: 300px;
      position: absolute;
      top: 50%;
      left: 50%;
      transform: translate(-50%,-50%);
    }
    #demo{
      position: absolute;
      top: 50%;
      left: 50%;
      transform: translate(-50%,-50%);
      font-size: 38px;
      color: #f3c623;
    }  
  </style>
  </head>
<body>
<span class="box">
<span id="demo"></span>
</span>
<script>
<?php

 


// here you can make timer.
  timer(5);
  // examples
  // timer(60); 
  // timer(32);
  // timer(4);
  ?>




</script>
</body>
</html>
