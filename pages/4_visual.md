---
title: Visualization
permalink: /visual/
---

## Visualization

<iframe id="data_visualization" src="https://nlp.biu.ac.il/~royi/hexagon-paper-visualization/#/main" title="Dataset Visualization" style="width:100%; height:720px; border:none;"></iframe>

<button id="full_screen" type="button" class="btn btn-primary btn-sm" onclick="fullScreen()">Go Full-Screen</button>

<script>
    function fullScreen() {
        var url = document.getElementById('data_visualization').src;
        window.location.replace(url);
        }
</script>