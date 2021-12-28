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

<div id="termynal"></div>
    <!-- include and initialise termynal.js -->
    <script src="/assets/js/termynal.js"></script>
    <script>
        var termynal = new Termynal('#termynal', {
            typeDelay: 40,
            lineDelay: 700,
            lineData: [
                { type: 'input', prompt: '▲', value: 'npm uninstall react' },
                { value: 'Are you sure you want to uninstall \'react\'?' },
                { type: 'input',  typeDelay: 1000, prompt: '(y/n)', value: 'y' },
                { type: 'progress', progressChar: '·' },
                { value: 'Uninstalled \'react\'' },
                { type: 'input', prompt:'▲', value: 'node' },
                { type: 'input', prompt: '>', value: `Array(5).fill('🦄 ')` },
                { value: `['🦄', '🦄', '🦄', '🦄', '🦄']` },
                { type: 'input', prompt: '▲', value: 'cd ~/repos' },
                { type: 'input', prompt: '▲ ~/repos', value: ' git checkout branch master' },
                { type: 'input', prompt: '▲ ~/repos (master)', value: 'git commit -m \'Fix things\'' },
            ]
        });
    </script>