<hr>


<html>

   <head>
      <title>Font Face</title>
   </head>

   <body>
      <font face = "Times New Roman" size = "5">Times New Roman</font><br />
      <font face = "Verdana" size = "5">Verdana</font><br />
      <font face = "Comic sans MS" size =" 5">Comic Sans MS</font><br />
      <font face = "WildWest" size = "5">WildWest</font><br />
      <font face = "Bedrock" size = "5">Bedrock</font><br />
   </body>

<style> .shakeimage{ position:relative } </style> <script language=”JavaScript1.2″> var rector=3 var stopit=0 var a=1 function init(which){ stopit=0 shake=which shake.style.left=0 shake.style.top=0 } function rattleimage(){ if ((!document.all&&!document.getElementById)||stopit==1) return if (a==1){ shake.style.top=parseInt(shake.style.top)+rector } else if (a==2){ shake.style.left=parseInt(shake.style.left)+rector } else if (a==3){ shake.style.top=parseInt(shake.style.top)-rector } else{ shake.style.left=parseInt(shake.style.left)-rector } if (a<4) a++ else a=1 setTimeout(“rattleimage()”,50) } function stoprattle(which){ stopit=1 which.style.left=0 which.style.top=0 } </script> <img src=”https://allthe2048.com/community-games/acotar-fanart.html” class=”shakeimage” onMouseover=”init(this);rattleimage()” onMouseout=”stoprattle(this);top.focus()” onClick=”top.focus()” width=”63″ height=”73″> 

</html>
