# workshop
2/20 台中workshop

學員可以clone回去用

##1. 引入lib 
	 
	 (範本中已引入)

   css: 
   ````<link rel="stylesheet" href="style.css">````

   javascript: 
   ````<script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.0.0-beta1/jquery.min.js"></script>````

##2. 基本排版

#### ui grid
最外層的grid容器，共分成 16 wide 的column

#### ui column
grid中的直向容器，搭配'xxx wide'指定寬度，一列上限為16。 
     e.g 
     ````
     		<div class="ui eight wide column">left</div>
     		<div class="ui eight wide column">right</div>
     ````
#### wide
搭配column使用，'xxx wide'指定寬度，xxx 為英文的數字，one, four, ten, ... twelve etc.
#### row
grid中的橫向容器，確保在row中，不超過16wide的column會在同一列，而不在row中的則自動換列

