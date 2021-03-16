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

![CVL](/images/OV2SLAM1.png){: style="float: left; margin-right: 1em;height: 150px; margin-top: 1.5em;width: 200px"} 
On présente qq articles et résultats sur le choix des paramètres d'optimisation d'un réseau (learning rate, batch size, etc.) et on s'interroge sur leur pertinence pour la segmentaiton sémantique.<!-- <normal> -->

Références

### 03.02.2021: BERT
#### William Grison

![BERT](/images/OV2SLAM1.png){: style="float: left; margin-right: 1em;height: 150px; margin-top: 1.5em;width: 200px"} 
Une présentation de BERT ()<!-- <normal> -->

