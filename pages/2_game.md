---
title: Game
permalink: /game/
---

## GAME

The Hexagons game is a 2-player instruction following game. 

<span style='font-size:20px;'>&#x1F481; <b> The Instructor </b> </span> <br/>
The Instructor gets a target image on the Hexagons board and has to provide instructions for how to draw the image step by step. <br/> 
Click the button to play the Instructor role.

<form action="https://nlp.biu.ac.il/~royi/hexagon-app-collection-demo/#/login">
	<button id="full_screen" type="button" class="btn btn-primary btn-sm" >Instructor Demo</button>
</form>

another button
<a href="https://nlp.biu.ac.il/~royi/hexagon-app-collection-demo/#/login" class="btn btn-primary btn-sm">Instructor Demo2</a>


<img src="../media/instructor_pane.png" alt="Instructor Pane" height="70%" width="auto">


<script>
    function fullScreen_ins() {
        var url = https://nlp.biu.ac.il/~royi/hexagon-app-collection-demo/#/login   		
        window.open(url, '_blank');        
        }        
    
</script>


<span style='font-size:20px;'>&#x1F481; <b> The Executor </b> </span> <br/>
The Executor gets the instructions and has to execute them one by one on a blank Hexagons board in order to reconstruct the target image. <br/>
Click here to play the Instructor role

<button id="full_screen" type="button" class="btn btn-primary btn-sm" onclick="fullScreen_ex()">Executor Demo</button>

<img src="../media/executor_pane.png" alt="Instructor Pane" height="70%" width="auto">

<script>
    function fullScreen_ex() {
        var url = https://nlp.biu.ac.il/~royi/hexagon-app-collection-demo/#/login   		
        window.open(url, '_blank');        
        }        
    
</script>

(Under construction)

[Home](/hexagonsDemo)




