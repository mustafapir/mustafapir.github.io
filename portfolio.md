---
title: Portfolio
layout: page
description: 
image: assets/images/tiles/portfolio.jpg
nav-menu: true
position: 1
---

<!-- Main -->
<div id="main">

<!-- One -->
<section id="intro"  class="background-accent6">
	<div class="inner">
		<header class="major">
			<h1>Portfolio</h1>
		</header>
		<p>This page contains links to some of my projects that showcase my competences in bioinformatics. The projects are grouped in:</p>
		<ul>
			<li><a href="#ml-projects" class="scrolly">Bioinformatics Projects</a></li>
			<li><a href="#bioinf-projects" class="scrolly">R/Shiny Projects</a></li>
		</ul>
	</div>
</section>


<section id="ml-projects" >
	<div class="inner">
		<header class="major">
			<h2>Bioinformatics Projects</h2>
		</header>
		<p>The following projects span a wide variety of bioinformatics topics, and are available on github.</p>
	</div>
</section>

<!-- Two -->
<section id="ml-projects-list" class="spotlights">
	<section>
		<a href="https://github.com/mustafapir" target="_blank" class="image" >
			<img src="{% link assets/images/portfolio/ciliogenics.png %}" alt="" data-position="center center" />
		</a>
		<div class="content">
			<div class="inner">
				<header class="major">
					<h3>CilioGenics</h3>
				</header>
				<p>This project consists of integrating protein interaction, comparative genomics, RNA-seq, data mining and motif data to find novel candidate ciliary genes.</p>
				<ul class="actions">
					<li><a href="https://github.com/mustafapir"  target="_blank" class="button">GitHub</a></li>
				</ul>
			</div>
		</div>
	</section>
	<section>
		<a href="https://convart.org" target="_blank" class="image" >
			<img src="{% link assets/images/portfolio/convart.jpg %}" alt="" data-position="center center" />
		</a>
		<div class="content">
			<div class="inner">
				<header class="major">
					<h3>ConVarT</h3>
				</header>
				<p>ConVarT is a search engine used to match human genetic variants with variants from non-human species. This repo contains pipeline to generate variant data and find matching variants between the species human, mouse and <i>C. elegans</i>. For more information, <a href="https://doi.org/10.1093/nar/gkab939"  target="_blank" class="link">click here</a>.</p>
				<ul class="actions">
					<li><a href="https://github.com/thekaplanlab/ConVarT_matchVar_analysis"  target="_blank" class="button">GitHub</a></li>
					<li><a href="https://convart.org"  target="_blank" class="button">Website</a></li>
				</ul>
			</div>
		</div>
	</section>
	<section>
		<a href="https://github.com/mustafapir" class="image">
			<img src="{% link assets/images/portfolio/comparative_genomics.png %}" alt="" data-position="top center" />
		</a>
		<div class="content">
			<div class="inner">
				<header class="major">
					<h3>Comparative Genomics Analysis</h3>
				</header>
				<p>This project explores the genes related to ciliogenesis through comparing genomes of 72 different organisms. It first blasts through genomic sequences to find orthologous genes, then clusters genes by generating phylogenetic tree via hierarchical clustering. Both bash and R scripts are used.</p>
				<ul class="actions">
					<li><a href="https://github.com/mustafapir"  target="_blank" class="button">GitHub</a></li>
				</ul>
			</div>
		</div>
	</section>
	<section>
		<a href="https://github.com/mustafapir" target="_blank" class="image" >
			<img src="{% link assets/images/portfolio/sc.png %}" alt="" data-position="center center" />
		</a>
		<div class="content">
			<div class="inner">
				<header class="major">
					<h3>Single Cell RNA-seq Analysis of Human Lung</h3>
				</header>
				<p>This notebook analyzes publicly available raw lung single cell RNA-seq data (<a href='https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE167295' > GSE167295 </a>) to find genes differentially expressed in ciliated cells. </p>
				<ul class="actions">
					<li><a href="https://github.com/mustafapir"  target="_blank" class="button">GitHub</a></li>
					<li><a href="https://notebooksharing.space/view/3744e371a4b36dd7a7451b187ef5d7b09a96175093e54d71882bc202dc01a5be"  target="_blank" class="button">R notebook</a></li>
				</ul>
			</div>
		</div>
	</section>
</section>


<section id="bioinf-projects"  class="background-accent5">
	<div class="inner">
		<header class="major">
			<h2>R/Shiny Projects</h2>
		</header>
		<p>The following projects span a wide variety of R packages and shiny apps.</p>
	</div>
</section>


<section id="bioinf-projects-list" class="custom-spotlights-accent5" >
	<section>
		<a href="https://github.com/mustafapir/orthoVar" target="_blank" class="image" >
			<img src="{% link assets/images/portfolio/orthoVar.png %}" alt="" data-position="center center" />
		</a>
		<div class="content">
			<div class="inner">
				<header class="major">
					<h3>orthoVar: an R Package for Finding Matching Variants Between Orthologous Protein Sequences Across Organisms.</h3>
				</header>
				<p>This R package is created to find matching amino acid variants between orthologous protein among different organisms. <code>orthoMSA</code> function is used to generate multiple sequence alignments by only providing organism names as input. Then <code>orthoFind</code> function can be used to find matching variants using generated msa table and user provided variant data.</p>
				<ul class="actions">
					<li><a href="https://github.com/mustafapir/orthoVar"  target="_blank" class="button">GitHub</a></li>
				</ul>
			</div>
		</div>
	</section>
	<section>
		<a href="https://ciliogenics.com" target="_blank" class="image" >
			<img src="{% link assets/images/portfolio/ciliogenics_web.png %}" alt="" data-position="center center" />
		</a>
		<div class="content">
			<div class="inner">
				<header class="major">
					<h3>CilioGenics Web App for Exploring Data.</h3>
				</header>
				<p>This shiny app is created to explore the data generated in <a href="#ml-projects" class="scrolly">CilioGenics project</a>. </p>
				<ul class="actions">
					<li><a href="https://github.com/thekaplanlab/CilioGenics-website"  target="_blank" class="button">GitHub</a></li>
					<li><a href="https://ciliogenics.com" class="button">Web</a></li>
				</ul>
			</div>
		</div>
	</section>
</section>


</div>
