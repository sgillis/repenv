# Reproducible environments

---

## Goal

<div>
<ul>
<li>Easy to set up for new devs, decrease onboarding time</li>
<li>Lightweight, cross platform, easy to understand solution</li>
<li>Package once, run anywhere</li>
<li>Close the gap between application and configuration management</li>
<li>Align development, testing, staging, production</li>
<li>Run multiple versions side by side</li>
</ul>
</div>
<!-- .element: class="fragment" -->

---

## The contenders

* Buildout
* Virtual machines
* Docker
* Debian/CentOS/... packages
* Virtualenv
* Conda
* Nix
* Pex (with Pants)

---

## The *real* contenders

* Buildout
* Virtual machines
* Docker
* <strike>Debian/CentOS/... packages</strike>
* <strike>Virtualenv</strike>
* <strike>Conda</strike>
* <strike>Nix</strike>
* <strike>Pex (with Pants)</strike>

---

## Buildout

### Pro

* Close to virtualenv spirit, but better
* Builds a simple .tar.gz which can be copied to production

---

## Buildout

### Con

* System dependencies
* Not used much outside Zope/Plone community, *lacking commercial interest*
* No easy solution for managing dependencies between services

---

## Virtual machines

### Pro

* Completely reproducible enviroment
* Very well proven tech
* *Used by industry giants (Adobe, Symantec, Hewlett-Packard, CapGemini, AT&T, Nokia, ...)*
---

## Virtual machines

### Con

* Slow and heavy

---

## Docker

### Pro

* Completely reproducible environment, much faster than VMs
* Managing and linking multiple services is easy
* *Easy to distribute, including versioning (push, pull via a docker registry)*
* *Used by industry giants (Google, Amazon, Spotify, ...)*

---

## Docker

### Con

* Newer technology

---

## Conclusion

1. Docker
2. VM's
3. Buildout
