---
layout: page
title: Proposal refined LODs for Buildings
permalink: /ongoingdev/tudelft-lods/
---

An ongoing development is to refine LODs of CityGML to provide a more precise LOD specification to precisely communicate the geometric detail of 3D city models.

The work is published in the following paper:

<div class="filteredelement"><strong>An improved LOD specification for 3D building models</strong>. Filip Biljecki, Hugo Ledoux, and Jantien Stoter. <em>Computers, Environment and Urban Systems</em>, 59: 25&ndash;37, 2016. <br /> <a href="http://filip.biljecki.com/publications/2016_ceus_improved_lod.pdf"><i class="fa fa-file-pdf-o"></i> PDF</a> <a href="http://doi.org/10.1016/j.compenvurbsys.2016.04.005"><i class="fa fa-external-link"></i> DOI</a> <a href="#bibBiljecki16c" data-toggle="collapse"><i class="fa fa-caret-square-o-down"></i> BibTeX</a><div id="bibBiljecki16c" class="collapse" tabindex="-1"><pre class="bibtex">@inproceedings{Biljecki16c,
  author = {Biljecki, Filip and Ledoux, Hugo and Stoter, Jantien},
  booktitle = {Computers, Environment and Urban Systems},
  pages = {25--37},
  title = {An improved {LOD} specification for {3D} building models},
  year = {2016},
  vol = {59},
  doi = {10.1016/j.compenvurbsys.2016.04.005}
}</pre></div></div>

In summary, according to the researchers the LOD concept found in CityGML 2.0 has two shortcomings:

* lack of a precise specification of each LOD; and that
* the current five LODs are too generic and therefore they are not always capable to separate one LOD from the other (i.e. two significantly different levels of abstraction may still be considered as the same LOD as per the current specification).

A refined specification is proposed, in which each LOD of CityGML is refined into 4 LODs, reflecting the capabilities of acquisition techniques and publicly available specifications. 


![](https://camo.githubusercontent.com/8af377060c48862f4af469a91bdcd172f2fc300c/68747470733a2f2f33642e626b2e747564656c66742e6e6c2f62696c6a65636b692f636f64652f696d672f52332d726566696e65644c4f44732e706e67){: width="600px"}