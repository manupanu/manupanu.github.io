---
layout: page
title: Über mich
subtitle: 
permalink: /
---

<div class="">
    <img class="profilephoto" src="/assets/img/Manuel_Portrait_bw_1x1.jpg">
</div>



<p>Mein Name ist <strong>Manuel Anrig</strong> und ich bin</p>

<div id="changeText"></div>

<script>
    var text = ["Elektroniker", "Web Entwickler", "ein kleiner Nerd"];
    var counter = 0;
    var inst = setInterval(change, 1000);

    function change() {
        document.getElementById("changeText");.innerHTML = text[counter];
        counter++;
        if (counter >= text.length) {
            counter = 0;
            // clearInterval(inst); // uncomment this if you want to stop refreshing after one cycle
        }
    }
</script>