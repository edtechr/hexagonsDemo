---
title: Visualization
permalink: /visual/
---

## Visualization


    <button id="full_screen" type="button" class="btn btn-primary btn-sm" onclick="fullScreen()">Go Full-Screen</button>
    <script>
    function fullScreen() {
        var url = document.getElementById('dataset_visualization').src;
        window.location.replace(url);
        }
    </script>