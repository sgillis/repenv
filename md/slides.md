# Reproducible environments

---

## Goal

<div>
<ul>
<li>CI/CD -> reproducible environments</li>
<li>Easy set up for new devs</li>
<li>Bring development, testing, staging, production closer together</li>
</ul>
</div>
<!-- .element: class="fragment" -->

---

## The contenders

* Virtualenv
* Buildout
* Virtual machines
* Debian/CentOS/... packages
* Conda
* Docker
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

Buildout is a Python-based build system

---

## Buildout

### Pro

* Close to virtualenv spirit, but better
* Builds a simple .tar.gz which can be copied to production

---

## Buildout

### Con

* System dependencies
* Not used much outside Zope/Plone community
* No easy solution for managing dependencies between services

---

## Virtual machines

### Pro

* Completely reproducible enviroment
* Very well proven tech

---

## Virtual machines

### Con

* Slow and heavy

---

## Docker

### Pro

* Completely reproducible environment
* Managing and linking multiple services is easy
* Much faster than VMs

---

## Docker

### Con

* Newer technology
