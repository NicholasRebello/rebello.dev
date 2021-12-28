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
<!-- <div id="termynal" data-termynal>
    <span data-ty="input">sudo apt install rebello.details</span>
    <span data-ty="progress"></span>
    <span data-ty>Successfully installed rebello.details</span>
    <span data-ty><a href="https://github.com/NicholasRebello">GitHub</a></span>
    <span data-ty><a href="https://linkedin.com/in/nicholas-rebello-7620b596">LinkedIn</a></span>
    <span data-ty><a href="https://twitter.com/Rebello_N">Twitter</a></span>
</div> -->

<!-- include and initialise termynal.js -->
<!-- <script src="/assets/js/termynal.js" data-termynal-container="#termynal"></script> -->

<!-- the termynal container -->
<div id="termynal"></div>

<!-- include and initialise termynal.js -->
<script src="/assets/js/termynal.js"></script>
<script>
    var termynal = new Termynal('#termynal', {
    typeDelay: 40,
    lineDelay: 600,
    lineData: [
        {value:'🆁🅴🅱🅴🅻🅻🅾.🅳🅴🆅'},
        {value:''},
        { type: 'input', prompt: '~', value: 'sudo apt install rebello.details' },
        { value: 'Are you sure you want to install \'rebello.details\'?' },
        { type: 'input',  typeDelay: 450, prompt: '(y/n)', value: 'y' },
        { type: 'progress', progressChar: '·' },
        { value: 'Installed \'rebello.details\'' },
        { prompt:'>', value: '<a href="https://github.com/NicholasRebello">GitHub</a>' },
        { prompt:'>', value: '<a href="https://linkedin.com/in/nicholas-rebello-7620b596">LinkedIn</a>' },
        { prompt:'>', value: '<a href="https://twitter.com/Rebello_N">Twitter</a>' },
    ]
    });
</script>