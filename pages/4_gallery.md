---
title: Gallery
permalink: /gallery/
---

## Visualization

<button id="full_screen" type="button" class="btn btn-primary btn-sm" onclick="fullScreen()">Go Full-Screen</button>

<iframe id="data_visualization" src="https://nlp.biu.ac.il/~royi/hexagon-paper-visualization-res/#/task-gallery" title="Dataset Visualization" style="width:100%; height:720px; border:none;"></iframe>

<script>
    function fullScreen() {
        var url = document.getElementById('data_visualization').src;
        window.open(url, '_blank');
        
        }
        
    
</script>
