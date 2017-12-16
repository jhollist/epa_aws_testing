# Versions
R and RStudio are both a bit on the old side.  As of my testing in Dec 2017, the instance was running R 3.4.1 and RStudio 1.0.153.  The most current in Dec 2017 are R 3.4.3 and RStudio 1.1.383.  Since these instances get built ad-hoc, be nice to have most recent versions built when the instance is built.

# Missing libraries
Number of missing libraries that will be part of "normal" use.  I define "normal" as what I general want when I build a fresh system.  No guarantees this covers all use cases.

- LaTeX
    - texlive 
    - texlive-latex-extra 
    - texlive-pictures
- Spatial Stuff
    - libgdal-dev 
    - libproj-dev
    - Need to also add the repository.  I typically use ppa:ubuntugis/ubuntugis-unstable
- Other
    - libxml2-dev
    - zlib1g-dev
    - libudunits2-dev (not sure on the libary name...)
    
    



