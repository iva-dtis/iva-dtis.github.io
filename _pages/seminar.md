---
layout: "single"
title: "Seminar"
permalink: "/seminar/"
author_profile: true

---

<script type="text/javascript">
   function toggleVisibility(block_id) {
       var e = document.getElementById(block_id);
       if(e.style.display == 'block')
          e.style.display = 'none';
       else
          e.style.display = 'block';
   }
    function copyToClip(element) {
        var str = document.getElementById(element).innerHTML;
        function listener(e) {
            e.clipboardData.setData("text/html", str);
            e.clipboardData.setData("text/plain", str);
            e.preventDefault();
        }
        document.addEventListener("copy", listener);
        document.execCommand("copy");
        document.removeEventListener("copy", listener);
};
</script>

this page reports on the seminar (or reading group) of the unit and offers associated documents (articles, presentations) 

### 03.16.2021: Sur la convergence des apprentissages
#### Adrien Chan Hon Tong

![Adrien](/images/imageAdrien.png){: style="float: left; margin-right: 1em;height: 150px; margin-top: 1.5em;width: 200px"} 
On présente qq articles et résultats sur le choix des paramètres d'optimisation d'un réseau (learning rate, batch size, etc.) et on s'interroge sur leur pertinence pour la segmentaiton sémantique. 
<!-- <normal> -->
<!-- <p style="text-align: right;"> -->
<br />
    <a href="https://drive.google.com/file/d/1CbD-WVXVha2RugW63501bksLZdxbEj6F/view?usp=sharing" style="color:page.header.overlay_color">[PDF]</a>
<!-- </normal> -->

Références : A compléter


### 03.02.2021: BERT
#### William Grison

![William](/images/imageWilliam.png){: style="float: left; margin-right: 1em;height: 150px; margin-top: 1.5em;width: 200px"} 
Une présentation de BERT (Bidirectional Encoder Representations from Transformers) depuis son introduction en NLP jusqu'à ses applications en Vision
<!-- <normal> -->
<!-- <p style="text-align: right;"> -->
<br />
    <a href="https://drive.google.com/file/d/11NNLZ1UEtXF3Vv0zvt4KW4ySgon2Kmlc/view?usp=sharing" style="color:page.header.overlay_color">[PDF]</a>
    <a href="https://youtu.be/eetNbgjV9VY" style="color:page.header.overlay_color">[Video]</a>
<!-- </normal> -->


### 11.01.2020: RL: from basics to Hindsight Experience Replay
#### Pierre Fournier

![Pierre](/images/imagePierre.png){: style="float: left; margin-right: 1em;height: 150px; margin-top: 1.5em;width: 200px"} 
Une introduction au deep reinforcement learning 
<!-- <normal> -->
<!-- <p style="text-align: right;"> -->
<br />
    <a href="https://drive.google.com/file/d/1t5ceLCuoPn-5rPSjnjOj6P4ASU5A8uet/view?usp=sharing" style="color:page.header.overlay_color">[PDF]</a>
<!-- </normal> -->
