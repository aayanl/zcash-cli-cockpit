# Zclassic-CLI-Cockpit

zclassic-cli cockpit plugin - a browser based wallet ui for zcash.

## Install Cockpit
Fedora Server comes with Cockpit installed.

Installing Cockpit in Ubuntu 16.04  
http://www.itzgeek.com/how-tos/linux/ubuntu-how-tos/install-cockpit-on-ubuntu-16-04.html

Access cockpit at the following url: https://localhost:9090/

## Install Zclassic

https://z.cash/download.html

Follow the <a target="_blank" href="https://github.com/z-classic/zclassic/wiki/1.0-User-Guide">Install Guide</a> to build zcash from source.

## Prepare your Linux system
Login to your linux server with your regular user account to get started.

    nproc and pidof commands are required to be functioning by this plugin.

zclassic-cli-cockpit plugin requires "zcash-cli" executable to be in your system path. It is possible to create a symbolic link to the "zcash-cli" binary.

    cd zcash_git_checkout_dir
    sudo ln -sr ./src/zcash-cli /usr/bin/zcash-cli

## Installing Zclassic-CLI-Cockpit plugin
Cockpit will search ~/.local/share/cockpit/ directory for plugins.

    mkdir ~/.local/share/cockpit/

Change directory and clone the git repository.
    
    cd ~/.local/share/cockpit/
    git clone https://github.com/aayanl/zclassic-cli-cockpit
    

Upgrading? Since there is no official relase at this time, you must "pull" the lastest from "master" using git.

    cd ~/.local/share/cockpit/zcash-cli-cockpit
    git pull

Open https://localhost:9090/ in your web browser and login to cockpit.
Look for a new menu entry under "Tools" called "zcash-cli".

# Donate to the project

ZCL -> t1JZgjgqN84otRFVNhUcJePTMNKH9JTf1eH

Orignial author
======
ZEC -> t1Qecf6zPTwWQ8eEhMHrux65gPQVYjKVDdq  
BTC -> 17v5jgu57wGKJnwkhVHvgYhbCVTFt9xXSN


<a target="_blank" href="http://z.cash/">z.cash</a> -> 
<a target="_blank" href="https://github.com/zcash/zcash/blob/master/doc/payment-api.md">1.0 Payment API</a> |
<a target="_blank" href="https://github.com/zcash/zcash/wiki/1.0-User-Guide">1.0 User Guide</a> |
<a target="_blank" href="https://github.com/zcash/zcash/wiki/Mining-Guide">Mining Guide</a> |
<a target="_blank" href="https://z.cash/support/faq.html">FAQ</a> |
<a target="_blank" href="https://forum.z.cash/">Forums</a>
