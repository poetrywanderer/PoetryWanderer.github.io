---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a Fourth-year Ph.D. student at [IRI-UPC](http://www.iri.upc.edu/) under the supervision of [Francesc Moreno-Noguer](http://www.iri.upc.edu/people/fmoreno/) 
and [Adria Ruiz](https://scholar.google.es/citations?user=h5cFva0AAAAJ&hl=ca). Before that, I received the Master's and Bachelor's degrees from Harbin Institute of Technology ([HIT](http://studyathit.hit.edu.cn/)) in China.

My research is in areas of computer vision and machine learning. Recently my focus lies in exploring the interpretability of 3D modeling, particularly the uncertainty associated with 3D models, with few source data.

## Publications
<style>
* {
  box-sizing: border-box;
}

/* Create two unequal columns that floats next to each other */
.column {
  float: left;
  padding: 0px;
}

.left {
  align-items: top;
  width: 30%;
}

.right {
  align-items: top;
  width: 68%;
}

.middle {
  align-items: top;
  width: 2%;
}
/* Clear floats after the columns */
.row:after {
  content: "";
  align-items: top;
  display: table;
  clear: both;
}

.content figure {
       width: 90%;
       display: flex;
       align-items: top;
       overflow: hidden;
       margin-left: auto!important;
       margin-right: auto!important;
      }
</style>

Here is a selection of recent publications, full list can be found on [Google Scholar](https://scholar.google.com/citations?user=1fkvaz4AAAAJ&hl=fr).

<!-- 2022 CF-NeRF -->
<article class="row">
  <div class="column left">
    <figure class="image">
      <img src="../images/2022-CF-NeRF.png" width="100%">
    </figure>
  </div>
  <div class="column middle">
    <figure class="image">
      <img src="../images/blank_placeholder.png" width="100%">
    </figure>
  </div>
  <div class="column right">
    <div class="content">
      <p>
        <b>Conditional-Flow NeRF: Accurate 3D modelling with Reliable Uncertainty Estimation</b><br>
        <b>Jianxiong Shen</b>, Antonio Agudo, Francesc Moreno-Noguer, Adria Ruiz<br>
        <i>ECCV 2022</i><br>
        <a href="https://poetrywanderer.github.io/CF-NeRF/" >Project Page</a>
        <a href="https://github.com/poetrywanderer/CF-NeRF" >Code</a>&nbsp;&nbsp;&nbsp;
        <!-- <a href="https://arxiv.org/abs/2207.01567" target="_blank">[paper]</a>
        <a href="https://github.com/dulucas/siMLPe" target="_blank">[Code]</a> -->
        &nbsp;&nbsp;&nbsp;
        <a onclick="javascript:ShowHide('#bibtex')" href="javascript:;">Bibtex</a></h5>
        <pre class='citation' id='bibtex' style="DISPLAY: none">
        @inproceedings{jshen2022cfnerf,
            Author = {Jianxiong, Shen and Agudo, Antonio and Moreno-Noguer, Francesc and Ruiz, Adria}
            Title = {Conditional-Flow NeRF: Accurate 3D modelling with Reliable Uncertainty Estimation},
            Year = {2022},
            booktitle = {ECCV},
        }
        </pre>
      </p>
    </div>
  </div>
</article>

<!-- 2021 3DV -->
<article class="row">
  <div class="column left">
    <figure class="image">
      <img src="../images/2021-S-NeRF.png" width="100%">
    </figure>
  </div>
  <div class="column middle">
    <figure class="image">
      <img src="../images/blank_placeholder.png" width="100%">
    </figure>
  </div>
  <div class="column right">
    <div class="content">
      <p>
        <b>Stochastic Neural Radiance Fields: Quantifying Uncertainty in Implicit 3D Representations</b><br>
        <b>Jianxiong Shen</b>, Adria Ruiz, Antonio Agudo, Francesc Moreno-Noguer<br>
        <i>3DV 2021 </i><br>
        <a href="https://poetrywanderer.github.io/CF-NeRF/" >Project Page</a>
        <a href="https://github.com/poetrywanderer/CF-NeRF" >Code</a>&nbsp;&nbsp;&nbsp;
        <!-- <a href="https://arxiv.org/abs/2207.01567" target="_blank">[paper]</a>
        <a href="https://github.com/dulucas/siMLPe" target="_blank">[Code]</a> -->
        &nbsp;&nbsp;&nbsp;
        <a onclick="javascript:ShowHide('#bibtex')" href="javascript:;">Bibtex</a></h5>
        <pre class='citation' id='bibtex' style="DISPLAY: none">
        @inproceedings{jshen2021snerf,
            Author = {Jianxiong, Shen and Ruiz, Adria and Agudo, Antonio and Moreno-Noguer, Francesc}
            Title = {Stochastic Neural Radiance Fields: Quantifying Uncertainty in Implicit 3D Representations},
            Year = {2021},
            booktitle = {3DV},
        }
        </pre>
      </p>
    </div>
  </div>
</article>

<!-- CF-NeRF -->
<div class="row"> <div class="col-md-3"><img style="height:120px;" alt src="https://www.albertpumarola.com/images/2020/ContextPred/context_pred_small.gif" style="width:80%; margin:10 px"> </div><div class="col-md-9"><h4>Conditional-Flow NeRF: Accurate 3D modelling with Reliable Uncertainty Estimation</h4><h5>Jianxiong Shen, Antonio Agudo, Francesc Moreno-Noguer, Adria Ruiz</h5> <h5>in <i>Proceedings of the European Conference on Computer Vision (ECCV), 2022 </i></h5><h5>
<a href="https://poetrywanderer.github.io/CF-NeRF/" >Project Page</a>
&nbsp;&nbsp;&nbsp;
<a href="https://arxiv.org/abs/2203.10192" >Paper</a>&nbsp;&nbsp;&nbsp;
<a href="http://www.iri.upc.edu/people/ecorona/lvd/" >Supplementary</a>&nbsp;&nbsp;&nbsp;
<a href="https://github.com/poetrywanderer/CF-NeRF" >Code</a>&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;
<a onclick="javascript:ShowHide('#bibtex')" href="javascript:;">Bibtex</a></h5>
<pre class='citation' id='bibtex' style="DISPLAY: none">
@inproceedings{jshen2022cfnerf,
    Author = {Jianxiong, Shen and Agudo, Antonio and Moreno-Noguer, Francesc and Ruiz, Adria}
    Title = {Conditional-Flow NeRF: Accurate 3D modelling with Reliable Uncertainty Estimation},
    Year = {2022},
    booktitle = {ECCV},
}
</pre>
</div></div>

<!-- S-NeRF -->
<div class="row"> <div class="col-md-3"><img style="width:200px;height:120px;" alt src="https://www.albertpumarola.com/images/2020/ContextPred/context_pred_small.gif" style="width:80%; margin:10 px"> </div><div class="col-md-9"><h4>Stochastic Neural Radiance Fields: Quantifying Uncertainty in Implicit 3D Representations</h4><h5>Jianxiong Shen, Adria Ruiz, Antonio Agudo, Francesc Moreno-Noguer</h5><h5>in <i>IEEE Conference on 3D Vision (3DV), 2021 </i></h5><h5>
<a href="http://www.iri.upc.edu/people/ecorona/lisa/" >Project Page</a>
&nbsp;&nbsp;&nbsp;
<a href="http://www.iri.upc.edu/people/ecorona/lisa/paper.pdf" >Paper</a>&nbsp;&nbsp;&nbsp;
<a href="http://www.iri.upc.edu/people/ecorona/lisa/supplementary.pdf" >Supplementary</a>&nbsp;&nbsp;&nbsp;
<!--<a href="https://github.com/enriccorona/YCB_Affordance" >Dataset</a>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<a href="https://github.com/enriccorona/GanHand" >Code</a>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;-->
&nbsp;&nbsp;&nbsp;
<a onclick="javascript:ShowHide('#corona2022lisa')" href="javascript:;">Bibtex</a></h5>
<pre class='citation' id='jshen2021snerf' style="DISPLAY: none">
@inproceedings{jshen2021snerf,
    Author = {Jianxiong, Shen and Ruiz, Adria and Agudo, Antonio and Moreno-Noguer, Francesc}
    Title = {Stochastic Neural Radiance Fields: Quantifying Uncertainty in Implicit 3D Representations},
    Year = {2021},
    booktitle = {3DV},
}
</pre>
</div></div>
