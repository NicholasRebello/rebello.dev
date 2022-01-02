---
layout: page
title: About
permalink: /about/
---
<!-- the termynal container -->
<div id="termynal"></div>

<!-- include and initialise termynal.js -->
<script src="/assets/js/termynal.js"></script>
<script>
    var termynal = new Termynal('#termynal', {
    typeDelay: 50,
    lineDelay: 900,
    lineData: [
        { class: "pink", value:'🆁🅴🅱🅴🅻🅻🅾.🅳🅴🆅'},
        { type: 'input', prompt: '~', value: 'sudo apt install rebello.details' },
        { type: 'input', prompt:'Enter Password for Sudo:', typeDelay: 120, value: '***********************'},
        { value: 'Are you sure you want to install \'rebello.details\'?' },
        { type: 'input',  typeDelay: 550, prompt: '(y/n)', value: 'y' },
        { type: 'progress', progressChar: '·' },
        { value: 'Installed \'rebello.details\'' },
        { prompt:'>', class: "red", value: 'About Nicholas Rebello'},
        { prompt:'>>', class: "yellow", value: 'Naval Reactor Operator & Network Adminisrator'},
        { prompt:'>', class: "red", value: 'Contact Information'},
        { prompt:'>>', class: "yellow", value: '<a href="https://github.com/NicholasRebello">GitHub</a>' },
        { prompt:'>>', class: "yellow", value: '<a href="https://linkedin.com/in/nicholas-rebello-7620b596">LinkedIn</a>' },
        { prompt:'>>', class: "yellow", value: '<a href="https://twitter.com/Rebello_N">Twitter</a>' },
        { prompt:'>>', class: "yellow", value: '<a href="mailto:blog.contact@rebz.anonaddy.com">Email</a>'},
    ]
    });
</script>