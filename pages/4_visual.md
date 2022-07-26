---
title: Visualization
permalink: /visual/
---

## Visualization1

<button id="full_screen" type="button" class="btn btn-primary btn-sm" onclick="fullScreen()">Go Full-Screen</button>

<iframe id="data_visualization" src="https://nlp.biu.ac.il/~royi/hexagon-paper-visualization/#/main" title="Dataset Visualization" style="width:100%; height:720px; border:none;"></iframe>

<script>
    function fullScreen() {
        var url = document.getElementById('data_visualization').src;
        window.open(url, '_blank');
        
        }
        
    // Selecting the iframe element
    var iframe = document.getElementById("data_visualization");
    
    // Adjusting the iframe height onload event
    iframe.onload = function(){
        iframe.style.height = iframe.contentWindow.document.body.scrollHeight + 'px';
    }
</script>
