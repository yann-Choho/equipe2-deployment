[![Construction image Docker](https://github.com/yann-Choho/Colorizing-puzzle-app-improved/actions/workflows/prod.yaml/badge.svg?branch=pierreBranch)](https://github.com/yann-Choho/Colorizing-puzzle-app-improved/actions/workflows/prod.yaml)
# ENSAE Paris | Institut Polytechnique de Paris

<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/e/ec/LOGO-ENSAE.png/900px-LOGO-ENSAE.png" width="300">

## Course : Mise en production des projets de data-science
### Lino GALIANA and Romain AVOUAC

### Academic year: 2023-2024
February 2024 - May 2024


## Topic : Machine Learning-Driven Image Colorization, a Puzzle Quest to Get Your Image Colorful 🎨

### Realised by :

* Yann Eric CHOHO
* Thomas PIQUÉ
* Pierre REGNARD

### Based on a former project for the course "Infrastructures et systèmes logiciels" with Antoine CHANCEL, realised by :

* Rayan TALATE
* Yseult MASSON
* Yann Eric CHOHO
* Thomas PIQUÉ
* Pierre REGNARD



</section>
<section id="track chosen :-dashboard-interactive-app" class="level3">
<h2 class="anchored" data-anchor-id="parcours-dashboard-application-interactive">Track chosen :dashboard-interactive-app</h2>
<div class="callout callout-style-default callout-tip callout-titled">
<div class="callout-header d-flex align-content-center">
<div class="callout-icon-container">
<i class="callout-icon"></i>
</div>
<div class="callout-title-container flex-fill">
<p><strong>Objective</strong> :</p>
</div>
</div>
<div class="callout-body-container callout-body">
<p>From an existing project or a new project, develop an interactive app or a <em>dashboard</em> addressing a business issue, then deploy it on a production infrastructure.</p>
</div>
</div>
<p><strong>Steps</strong> :</p>
<ul class="task-list">
<li><label><input type="checkbox">Fulfil the <em>checklist</em> of development best practices</label></li>
<li><label><input type="checkbox">Develop an interactive app <code>Streamlit</code> or a static <em>dashboard</em> with <code>Quarto</code> addressing a business issue</label></li>
<li><label><input type="checkbox">Create a <code>Docker</code> image for the local application</label></li>
<li><label><input type="checkbox">Deploy the app on <code>SSP Cloud</code> (interactive app) or on <code>Github Pages</code> (static website)</label></li>
<li><label><input type="checkbox">Customize the theme, the CSS etc. to best highlight the publication results and its main takeaway</label></li>
<li><label><input type="checkbox">Automate the ingestion of input data so that the <em>website</em> updates regularly</label></li>
<li><label><input type="checkbox">Industrialize deployment in <code>GitOps</code> mode with <code>ArgoCD</code></label></li>
<li><label><input type="checkbox">Monitor the app : <em>logs</em>, performance metrics, etc.</label></li>
</ul>


</div>
</div>
</section>
<section id="Checklist of development good practices" class="level2">
<h2 class="anchored" data-anchor-id="checklist-des-bonnes-pratiques-de-développement">Checklist of development good practices</h2>
<p>Below development good practices are a <strong>requirement of this course</strong>. They have to be applied to both <strong>group projects<strong> and </strong>individual code reviews</strong>.</p>
<ul class="task-list">
<li><label><input type="checkbox"><strong><code>Git</code></strong> usage </label>
<ul>
<li>Presence of a <code>.gitignore</code> file adapted to the language and with additional rules to respect good versioning practices</li>
<li>Collaborative work : use of branches and <em>pull requests</em></li>
</ul></li>
<li><label><input type="checkbox"><strong>Presence of a <code>README</code></strong> file introducing the project : context, objective, how to use it ?</label></li>
<li><label><input type="checkbox"><strong>Presence of a <code>LICENSE</code></strong> file stating the licence (<em>open-source</em>) for project exploitation.</label></li>
<li><label><input type="checkbox"><strong>Versioning of packages</strong> : presence of a <code>requirements.txt</code> file / environment file <code>environment.yml</code> for <code>conda</code></label></li>
<li><label><input type="checkbox"><strong>Code quality </strong></label>
<ul>
<li>Respect of community standards  : use a <em>linter</em> or a <em>formatter</em></li>
<li>Modularity : a main script calling modules</li>
</ul></li>
<li><label><input type="checkbox"><strong>Projects structure</strong></label>
<ul>
<li>Respect of community standards (<code>cookiecutter</code>)</li>
<li>Project modularity according to the model mentioned in the course:
<ul>
<li>Code on <code>GitHub</code></li>
<li>Data on <code>S3</code></li>
<li>Separated configuration files (<em>secrets</em>, etc.)</li>
</ul></li>
</ul></li>
</ul>


## Introduction

This application allows you to solve a puzzle of a black-and-white image. Once the puzzle is finished, the image is colorized by a Deep Learning model and appears on your screen! \
On the menu page, you can choose between 2 types of puzzle : sliding puzzle and free movement puzzle.

This repository contains all files allowing to deploy the application. The main repository for the application is available below. 


## Link to the CD git repo 
By using this link [this link](https://github.com/yann-Choho/Colorizing-puzzle-app-improved.git), you can access the git repository containing all the scripts used to set up the application

## Link to the website of the application
By using [this link](https://puzzle.kub.sspcloud.fr/), you can access directly the website application and enjoy it !
