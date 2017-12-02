# read-post-using-js


-Read post data using javascript.  

First method 

-single landing page

equivalent to php  $_ISSET   



Second method 

equivalent to  php  

$_a=new array();  // array where all post data will be stored
foreach($_POST as $key => $value)
{
   $message = "$key => $value\n";
//echo $message;

array_push($_a,$key,$value);
  }       


