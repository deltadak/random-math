Automatically installing the required packages on TeX Live
----------------------------------------------------------

Copy the `texliveonfly.py` file next to your main `.tex` file, and run `sudo python texliveonfly.py main.tex` which will install the required packages.
It can handle LaTeX packages contained in a TeX Live package with a different name, and package dependencies.


Source: https://latex.org/forum/viewtopic.php?t=15194

Also see https://github.com/Strauman/travis-latexbuild/issues/21