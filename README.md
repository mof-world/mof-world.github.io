---
layout: page
title: mof.world
tagline: "mof.world: tools for digital reticular chemistry"
description: >-
    Reticular chemistry provides us with an enourmous design space. 
    Using digital tools we can efficiently explore this space. 
    mof.world collects tools that help in this process. 
---
<style>
    .header {grid-area: header;}
    .footer {grid-area: footer;}
    .main1  {grid-area: main1;}


    .grid-container {
        display: grid;
        grid-template-areas:
            'header'
            'main1'
            'main2'
            'main3'
            'footer';
        gap: 10px;
        padding: 10px;
    }
    
    .grid-container > div {
        text-align: center;
        font-size: 18px;
    }

</style>
<div class="grid-container">
    <div class="header">
        <div style="display: table-cell; vertical-align: middle; 
        min-width: 120px; min-height: 120px; max-width: 120px; max-height: 120px">
            <img src="images/dalle-mini.jpg" alt="mofworld">
        </div>
        <div style="display: table-cell; vertical-align: middle">
            <h2> <i>mof.world</i>: tools for digital reticular chemistry</h2>
        </div>
        <hr/>
    </div>
    <div class="main1">
        <img src="images/mofdscribe.png" alt="mofdscribe" width="200"/><br/>
        <a href="https://mofdscribe.readthedocs.io"><img src="https://badgen.net/badge/docs/mofdscribe.readthedocs.io/grey?icon=firefox"></a><br/>
        <a href="https://github.com/kjappelbaum/mofdscribe"><img src="https://badgen.net/github/tag/kjappelbaum/mofdscribe/?icon=github"></a><br/>
        <a href="https://pypi.org/project/mofdscribe"><img src="https://badgen.net/pypi/v/mofdscribe/?icon=pypi"></a><br/>
    </div>
    <div class="main2">
        <img src="images/moffragmentor.png" alt="moffragmentor" width="400"/><br/>
        <a href="https://moffragmentor.readthedocs.io"><img src="https://badgen.net/badge/docs/moffragmentor.readthedocs.io/grey?icon=firefox"></a><br/>
        <a href="https://github.com/kjappelbaum/moffragmentor"><img src="https://badgen.net/github/tag/kjappelbaum/moffragmentor/?icon=github"></a><br/>
        <a href="https://pypi.org/project/moffragmentor"><img src="https://badgen.net/pypi/v/moffragmentor/?icon=pypi"></a><br/>
    </div>
    <div class="main3">
        <img src="images/mofchecker.png" alt="mofchecker" width="400"/><br/>
        <a href="https://mofchecker.readthedocs.io"><img src="https://badgen.net/badge/docs/mofchecker.readthedocs.io/grey?icon=firefox"></a><br/>
        <a href="https://github.com/kjappelbaum/mofchecker"><img src="https://badgen.net/github/tag/kjappelbaum/mofchecker/?icon=github"></a><br/>
        <a href="https://pypi.org/project/mofchecker"><img src="https://badgen.net/pypi/v/mofchecker/?icon=pypi"></a><br/>
    </div>
    <div class="footer">
        <hr/>
        <p>
            Devlopment led at <img src="https://www.epfl.ch/wp/5.5/wp-content/themes/wp-theme-2018/assets/svg/epfl-logo.svg" alt="epfl" height="20"/>  by
            <a href="https://kjablonka.com"> Kevin M Jablonka</a> in the <a href="https://www.epfl.ch/labs/lsmo/">  Laboratory of Molecular Simulation</a><br/>
            © 2021-2022
        </p>
    </div>
</div>