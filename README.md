# badducklabs.github.io

How to install Hugo:

Follow the instruction https://gohugo.io/overview/installing/

How to build and deploy a site
1) Build a site:
- $ cd badducklabs.github.io/src/
- $ hugo

It will update the content of a badducklabs.github.io/src/public/ folder.

2) Deploy it:
- remove all the content of a badducklabs.github.io folder EXCEPT for src/ folder and README.md file (and, obviously, the .git folder).
- copy the content of a badducklabs.github.io/src/public/ folder to badducklabs.github.io/
- push it to server
- GitHub pages will deploy the site during 5-10 minutes


Agency theme tutorial: http://themes.gohugo.io/agency/