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
        { value:'🆁🅴🅱🅴🅻🅻🅾.🅳🅴🆅'},
        { type: 'input', prompt: '~', value: 'sudo apt install rebello.details' },
        { type: 'input', prompt:'Enter Password for Sudo:', typeDelay: 120, value: '************************'},
        { value: 'Are you sure you want to install \'rebello.details\'?' },
        { type: 'input',  typeDelay: 550, prompt: '(y/n)', value: 'y' },
        { type: 'progress', progressChar: '·' },
        { value: 'Installed \'rebello.details\'' },
        { prompt:'>', color: "red", value: 'About Nicholas Rebello'},
        { prompt:'>>', value: 'Naval Reactor Operator & Network Adminisrator'},
        { prompt:'>', value: 'Contact Information'},
        { prompt:'>>', value: '<a href="https://github.com/NicholasRebello">GitHub</a>' },
        { prompt:'>>', value: '<a href="https://linkedin.com/in/nicholas-rebello-7620b596">LinkedIn</a>' },
        { prompt:'>>', value: '<a href="https://twitter.com/Rebello_N">Twitter</a>' },
        { prompt:'>>', value: '<a href="mailto:blog.contact@rebz.anonaddy.com">Email</a>'},
    ]
    });
</script>