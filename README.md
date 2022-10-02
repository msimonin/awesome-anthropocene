A not curated list of awesome anthropocene facts, impact, study ... before the collapse.

# Technology

- Sabine Hossenfelder: [Flying green](http://backreaction.blogspot.com/2022/10/can-we-make-flying-green.html)
    + related papers: [Electric Flight – Potential and Limitations](https://www.mh-aerotools.de/company/paper_14/MP-AVT-209-09.pdf)


# People


# (FR)

- Research strategy: [sciences citoyennes](https://sciencescitoyennes.org/)
- [Romain Couillet](http://polaris.imag.fr/romain.couillet)


# Usage of this repo

Some of the content is pushed as an git-annex so you'll need git-annex installed.

The required deps using guix look like:
```bash
guix shell -C -N --expose=$HOME/.gitconfig --expose=$HOME/.ssh --expose=/etc/ssl/certs --expose=/etc/protocols coreutils git git-annex vim nss-certs openssl openssh-sans-x
```