A not curated list of awesome anthropocene facts, impact, study ... before the
collapse.

Some file (marked with 🗃️) are expected to be big so `git-annex` is used for
that (this doesn't store the file, only a link to a file somewhere in the
internet).

# Technology

- Sabine Hossenfelder: [Flying green](http://backreaction.blogspot.com/2022/10/can-we-make-flying-green.html)
    + 🗃️ related papers: [Electric Flight – Potential and Limitations](https://www.mh-aerotools.de/company/paper_14/MP-AVT-209-09.pdf)


# People

- (FR)[Romain Couillet](http://polaris.imag.fr/romain.couillet)


# Research directions

- 🇫🇷 [sciences citoyennes](https://sciencescitoyennes.org/)
- 🇫🇷 🗃️ [Petit manuel du déraillement](http://polaris.imag.fr/romain.couillet/docs/articles/TS_diplomatie.pdf)

# Usage of this repo

The required deps using guix look like:
```bash
guix shell -C -N --expose=$HOME/.gitconfig --expose=$HOME/.ssh --expose=/etc/ssl/certs --expose=/etc/protocols coreutils git git-annex vim nss-certs openssl openssh-sans-x
```