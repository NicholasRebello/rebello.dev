---
# the default layout is 'page'
icon: fas fa-info-circle
order: 4
---

<!-- the termynal container -->
<div id="termynal"></div>
<!-- include and initialise termynal.js -->
<script src="/assets/js/termynal.js"></script>
<script>
    var termynal = new Termynal('#termynal', {
    typeDelay: 50,
    lineDelay: 500,
    lineData: [
        { type: 'input', prompt: '~', value: 'sudo apt install rebello.details' },
        { type: 'input', prompt:'Enter Password for Sudo:', typeDelay: 120, value: '           '},
        { value: 'Are you sure you want to install \'rebello.details\'?' },
        { type: 'input',  typeDelay: 550, prompt: '(y/n)', value: 'y' },
        { type: 'progress', progressChar: '·' },
        { value: 'Installed \'rebello.details\'' },
        { prompt:'>', class: "red", value: 'About Nicholas Rebello'},
        { prompt:'>>', class: "yellow", value: 'Cybersecurity Specialist / Systems Administrator'},
        { prompt:'>>', class: "yellow", value: 'GCIH | GSEC | Security+ | Network+'},
        { prompt:'>>', class: "yellow", value: 'EFF Member since 2021'},
        { prompt:'>>', class: "yellow", value: 'Privacy Advocate and Technology Enthusiast'},
        { prompt:'>', class: "red", value: 'Contact Information'},
        { prompt:'>>', class: "yellow", value: '<a href="https://github.com/NicholasRebello">GitHub</a>' },
        { prompt:'>>', class: "yellow", value: '<a href="https://linkedin.com/in/Nicholas-Rebello">LinkedIn</a>' },
        { prompt:'>>', class: "yellow", value: '<a rel="me" href="https://infosec.exchange/@rebello">Mastodon</a>' },
        { prompt:'>>', class: "yellow", value: '<a href="mailto:blog.contact@rebello.dev">Email</a>'},
    ]
    });
</script>