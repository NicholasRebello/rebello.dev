---
layout: page
title: About
permalink: /about/
---
<!-- ![Rebello]({{ "/assets/rebello.png" | relative_url }})

**This page is a work in progress**

Welcome to my portfolio/blog site! Here you will find documentation on my journey into the world of information security. Currently enlisted in the Navy; working with nuclear power and administering my departments internal network.

* <a href="https://github.com/NicholasRebello">GitHub</a>
* <a href="https://linkedin.com/in/nicholas-rebello-7620b596">LinkedIn</a>
* <a href="https://twitter.com/Rebello_N">Twitter</a>  -->

<!-- the termynal container -->
<div id="termynal" data-termynal>
    <span data-ty="input">pip install spacy</span>
    <span data-ty="progress"></span>
    <span data-ty>Successfully installed spacy</span>
    <span data-ty></span>
    <span data-ty="input">python -m spacy download en</span>
    <span data-ty="progress"></span>
    <span data-ty>Installed model 'en'</span>
    <span data-ty></span>
    <span data-ty="input">python</span>
    <span data-ty="input" data-ty-prompt=">>>">import spacy</span>
    <span data-ty="input" data-ty-prompt=">>>">nlp = spacy.load('en')</span>
    <span data-ty="input" data-ty-prompt=">>>">doc = nlp(u'Hello world')</span>
    <span data-ty="input" data-ty-prompt=">>>">print([(w.text, w.pos_) for w in doc])</span>
    <span data-ty>[('Hello', 'INTJ'), ('world', 'NOUN')]</span>
</div>

<!-- include and initialise termynal.js -->
<script src="/assets/js/termynal.js" data-termynal-container="#termynal"></script>