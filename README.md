Sublime 2:

step1.Install package control
ctrl + `
type in: 
import urllib2,os; pf='Package Control.sublime-package'; ipp=sublime.installed_packages_path();

step2.
cmd + shift + p
laTexTools

step3. install xelatex
Tools -> Build System -> New Build System …
Type in the code of XeLatTex.xublime-build

Save the change: cmd + s

step4. If there is a problem of migration preference
Go to command palette(cmd + shift + p)
type in:
LaTeXTools: Reconfigure and migrate settings
Enter

step5. Make sure you have checked 
Tools -> Build System -> XeLaTex
