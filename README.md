
Use this repository for reporting arch-specific bugs and feature requests.

Normally you won't be using the pkgbuilds in this repo directly.  Instead add the `any` repo and your architecture's repo to your `pacman.conf`

    [outernet-any]
    Server = http://archive.outernet.is/repo/outernet-any/
    
    [outernet-i686]
    Server = http://archive.outernet.is/repo/outernet-i686/
    
    [outernet-x86_64]
    Server = http://archive.outernet.is/repo/outernet-x86_64/
    
Then you may `pacman -S python2-librarian`



