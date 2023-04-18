## Portfolio website

Code to generate a simple portfolio website with my photography projects. 
Live at https://egazzarr.github.io/portfolio/. 
The deployment and build is activated through github pages on the `main` branch. 
The website is built with [hugo](https://gohugo.io); if you are interested in replicating this, follow the documentation of the [sourdough](https://github.com/Jack-alope/sourgough-starter).

- *.github/workflows*: automatically updates the website online every time something is pushed to the `main` branch. 
- *content*: to set what you see in the url
- *docs*: gets generated after running the `hugo` command to build the site. In fact, in the config.toml there is a reference to this folder. 
- *js*: potential scroll-over functions for the mindmap
- *layouts*: add photos and folders here wheneer you want to change images
- *static*: contains the `css` theme and a folder with all the `images`

In order to edit the site and publish it, change the contect of `layouts`. Run the `hugo serve -D` command on the terminal to view local edits. Run `hugo` from the directory where you have the `config.toml` file and it will update the `/docs` fodler, from which the `workflows` to build the website pick up. 
