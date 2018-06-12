---
permalink: /gallery/
title: "Lab Happenings"
author_profile: true
redirect_from: 
  - /md/
---
<html>
<head>
<link rel="stylesheet" href="/css/blueimp-gallery.min.css">
</head>

<body>

<!-- The Gallery as inline carousel, can be positioned anywhere on the page -->
<div id="blueimp-gallery-carousel" class="blueimp-gallery blueimp-gallery-carousel">
    <div class="slides"></div>
    <h3 class="title"></h3>
    <a class="prev">‹</a>
    <a class="next">›</a>
    <a class="play-pause"></a>
    <ol class="indicator"></ol>
</div>

<div id="links">
    <a href="/images/gallery/IMGP9128.jpg" title="Lander2018">
        <img src="/images/gallery/IMGP9128.jpg" alt="Lander2018">
    </a>
    <a href="/images/gallery/Yellowstone2017_13.jpg" title="SpearLabYNP">
        <img src="/images/gallery/Yellowstone2017_13.jpg" alt="SpearLabYNP">
    </a>
    <a href="/images/gallery/37908919361_7caeaa3a3e_o.jpg" title="JohnMobe">
        <img src="/images/gallery/37908919361_7caeaa3a3e_o.jpg" alt="JohnMoBE">
    </a>
    <a href="/images/gallery/37908861621_be41f9cf4e_o.jpg" title="MoBE2017">
        <img src="/images/gallery/37908861621_be41f9cf4e_o.jpg" alt="MoBE2017">
    </a>
    <a href="/images/gallery/IMGP9451.jpg" title="MarrRMGS2018">
        <img src="/images/gallery/IMGP9451.jpg" alt="MarrRMGS2018">
    </a>
</div>

<script>
blueimp.Gallery(
    document.getElementById('links').getElementsByTagName('a'),
    {
        container: '#blueimp-gallery-carousel',
        carousel: true
    }
);
</script>

</body>
</html>