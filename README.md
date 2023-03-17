## Portfolio website

Code to generate a simple portfolio website with my photography projects. 
Live at https://egazzarr.github.io/portfolio/. 
The deployment and build is activated through github pages on the `right` branch. 
The website is built with [hugo](https://gohugo.io); if you are interested in replicating this, follow the documentation of the [sourdough](https://github.com/Jack-alope/sourgough-starter).

- *content*: to set what you see in the url
- *js*: potential scroll-over functions for the mindmap
- *layouts*: add photos and folders here wheneer you want to change images
- *public*: gets generated after running the `hugo` command to build the site. In fact, in the config.toml there is a reference to this folder. 
- *static*: contains the `css` theme and a folder with all the `images`

In order to edit the site and publish it, change the contect of `layouts` and then run the `hugo -D` command. 
The github actions and the pages set up will automatically apply the changes online. 