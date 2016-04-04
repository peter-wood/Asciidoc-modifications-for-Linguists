# Asciidoc Modifications for Linguists

This is a collection of backends, plugins, and shell scripts I have adapted to my needs. I hope someone might find them
useful. 

What you find here:

- A **.asciidoc** directory. Copy it into your home directory
- Copy the files in **.asciidoc/bash**' into your **~/bin** directory
- The **mktemplate** script will create an asciidoc template in your current working directory
- The **knitr** is a wrapper around R's **knit** command
- The **slidy2** backend has been modified to work with Chrome (toggling of color-schemes does not work in the original
  version)
- The **ling** plugin is a modified version of the **latex** plugin that comes with asciidoc. I have added usepackage
  statements to include packages to draw trees and to create glosses (basic examples are provided in the templates). Image generation defaults to svg which looks and scales nicer than png and is now supported on most browsers

If you encounter errors, please contact me. But please make sure that you have installed the required packages first:

- asciidoc (use the current git version)
- latex (obviously)
- latex packages: qtree, gb4e
- dvi2svgm 
- R (obviously)
- ascii library for R

Some path names might need  to be changed to adapt the scripts to your system.
