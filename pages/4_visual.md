---
title: Visualization
permalink: /visual/
---

## Visualization

<p align="center">
<iframe src="https://nlp.biu.ac.il/~royi/hexagon-paper-visualization/#/main" id="procedureFrame" style="width:100%; height:720; border:none;" frameBorder="50"></iframe>
</p>
    <button id="full_screen" type="button" class="btn btn-primary btn-sm" onclick="fullScreen()">Go Full-Screen</button>
    <script>
    // Selecting the iframe element
    var iframe = document.getElementById("procedureFrame");
    
    // Adjusting the iframe height onload event
    iframe.onload = function(){
        iframe.style.height = iframe.contentWindow.document.body.scrollHeight + 'px';
    }
    </script>