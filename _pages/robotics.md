---
layout: "single"
title: "Robotics"
permalink: "/robotics/"
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

## Visual Localization
### OV2SLAM: Online Versatile Visual SLAM
#### Maxime Ferrera, Alexandre Eudes, Julien Moras, Martial Sanfourche and Guy Le Besnerais

![OV2SLAM](/images/OV2SLAM1.png){: style="float: left; margin-right: 1em;height: 150px; margin-top: 1.5em;width: 200px"} 
Many applications of Visual SLAM, such as augmented reality, virtual reality, robotics or autonomous driving, require versatile, robust and precise solutions, most often with
real-time capability. We propose a fully online algorithm, handling both monocular and stereo camera setups, various map scales and frame-rate ranging from a few Hertz up to several hundreds. It combines numerous recent contributions in visual localization within an efficient multi-threaded architecture.
<!-- <normal> -->
<!-- <p style="text-align: right;"> -->
<br />
    <a href="https://github.com/ov2slam" style="color:page.header.overlay_color">[GitHub]</a>
<!-- </normal> -->
