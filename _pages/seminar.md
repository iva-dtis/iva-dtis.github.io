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

this page reports on the seminar (or reading group) of the unit and offers associated documents (slides, video, references) 



### 13 avril 2021: Sur les graphes de connaissances
#### Baptiste Abeloos

![Baptiste](/images/imageBaptiste.png){: style="float: left; margin-right: 1em;height: 150px; margin-top: 1.5em;width: 200px"} 
Introduction aux graphes de connaissances, à la notion de prédiction de liens, et présentation de l'article ConceptBert
<!-- <normal> -->
<!-- <p style="text-align: right;"> -->
<br />
    <a href="https://drive.google.com/file/d/1CioMAylEMlT0pJLEHqrYtkgCN6pkSeB2/view?usp=sharing" style="color:page.header.overlay_color">[PDF]</a>
<!-- </normal> -->




### 16 mars 2021: Sur la convergence des apprentissages
#### Adrien Chan Hon Tong

![Adrien](/images/imageAdrien.png){: style="float: left; margin-right: 1em;height: 150px; margin-top: 1.5em;width: 200px"} 
On présente qq articles et résultats sur le choix des paramètres d'optimisation d'un réseau (learning rate, batch size, etc.) et on s'interroge sur leur pertinence pour la segmentation sémantique. 
<!-- <normal> -->
<!-- <p style="text-align: right;"> -->
<br />
    <a href="https://drive.google.com/file/d/1CbD-WVXVha2RugW63501bksLZdxbEj6F/view?usp=sharing" style="color:page.header.overlay_color">[PDF]</a>
<!-- </normal> -->

Références : 
* 2006.15081 (deepmind) On the Generalization Benefit of Noise in Stochastic Gradient Descent
* 1907.04595 (Carnegie) Towards Explaining the Regularization Effect of Initial Large Learning Rate in Training Neural Networks
* 1907.04164 (deepmind) Which Algorithmic Choices Matter at Which Batch Sizes? Insights From a Noisy Quadratic Model
* 1704.04289 (Columbia) Stochastic Gradient Descent as Approximate Bayesian Inference
* Nips2019 (Chicago + Israël) Stochastic Gradient Descent on Separable Data: Exact Convergence with a Fixed Learning Rate


### 2 mars 2021: BERT
#### William Grison

![William](/images/imageWilliam.png){: style="float: left; margin-right: 1em;height: 150px; margin-top: 1.5em;width: 200px"} 
Une présentation de BERT (Bidirectional Encoder Representations from Transformers) depuis son introduction en NLP jusqu'à ses applications en Vision.
<!-- <normal> -->
<!-- <p style="text-align: right;"> -->
<br />
    <a href="https://drive.google.com/file/d/11NNLZ1UEtXF3Vv0zvt4KW4ySgon2Kmlc/view?usp=sharing" style="color:page.header.overlay_color">[PDF]</a>
    <a href="https://youtu.be/eetNbgjV9VY" style="color:page.header.overlay_color">[Video]</a>
<!-- </normal> -->

Références :
* Devlin, J., Chang, M. W., Lee, K., & Toutanova, K. (2018). Bert: Pre-training of deep bidirectional transformers for language understanding. arXiv preprint arXiv:1810.04805.

### novembre 2020: RL: from basics to Hindsight Experience Replay
#### Pierre Fournier

![Pierre](/images/imagePierre.png){: style="float: left; margin-right: 1em;height: 150px; margin-top: 1.5em;width: 200px"} 
Une introduction au deep reinforcement learning 
<!-- <normal> -->
<!-- <p style="text-align: right;"> -->
<br />
    <a href="https://drive.google.com/file/d/1t5ceLCuoPn-5rPSjnjOj6P4ASU5A8uet/view?usp=sharing" style="color:page.header.overlay_color">[PDF]</a>
<!-- </normal> -->
