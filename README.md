TeX Beamer Template
---

This repo contains the LaTeX Beamer template I've created for my own use at the W.P. Carey School of Business. It is a modified version of [this Beamer theme](http://www.drbunsen.org/custom-beamer-theme.html) created by Seth Brown.

I tried to stay as true as I could to the ASU Brand Marketing guidelines, using the official shades of maroon and gold, along with the sanctioned ASU WPC logo.

#### Features
* ASU WPC logo always centered on title page
* Short title placed in bottom left footer
* Page numbers in bottom right footer
* Section headings in upper right header
* Minimal other distractions

#### Usage

There are two ways to use this theme. The first is to simply place the files in the folder of your TeX document. This can be done by clicking Download ZIP above or by cloning the repository using GitHub.
To clone the repository, navigate to your working directory and use

```bash
$ git clone git@github.com:tbeason/wpc-beamer.git
```
In the preamble of your presentation, remember to set the theme with ``\usetheme{wpc-beamer/wpc}`` (or if you did not place them in their own folder) ``\usetheme{wpc}``.

The second way to use the theme is to place them where MiKTeX can see them and then refresh its FNDB. Follow these [instructions](http://docs.miktex.org/faq/faq.html#styfiles).

#### Contact

[tbeason.com](http://tbeason.com)
