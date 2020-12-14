<!DOCTYPE html>
<html>
<head>
	<title>Guessing Number</title>
</head>
<body>
	
	<script>
		var Guessing;
		Guessing = window.prompt("Please guess a number from 1 to 10")
		var num;
		num = Math.floor((Math.random()*10)+1);

		number = parseInt(num);
		again  = parseInt(Guessing);
	
	  while(number!=again){
	   	 again = window.prompt("Please guess another number")
	  }
	   
	   	alert("Congratulation")
	   
	    
		
		
     </script>


</body>
</html>
