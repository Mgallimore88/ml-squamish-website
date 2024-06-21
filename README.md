

1. To install Quarto, head to vscode and install the quarto extension. 

2. Fork this repo to grab the website. Once you're in the project, changes can be previewed in vscode using the render button, or with shortcut CMD + Shift + P then choosing >quarto>render. 

To preview the page, find the main index.qmd and preview with CMD + Shift + K

The website is rendered to the docs directory, and this is the folder which github pages looks at for the website. 

3. Create a pull request to merge changes to publish your edits to the website. 

4. A blog post can just be a jupyter notebook in a new folder within past-events. If you choose this option, then follow these steps to display the date and author correctly in the blog index:
- add a new cell to the top of the .ipynb file
- change the cell type to 'raw' by clicking the bottom right corner of the cell. 
- include the same header info and any markdown text to introduce the blog post from another similar ipynb file. 
- There is no need to also include an index.qmd for this post - the jupyter notebook and header cell will be rendered as a blog post. 

5. If the content is in the form of a slideshow or PDF, your best option is to create an index.qmd page for the event, then link to the google doc hosting the pdf or powerpoint presentation. 

Optional themes:


    default
    cerulean
    cosmo
    cyborg
    darkly
    flatly
    journal
    litera
    lumen
    lux
    materia
    minty
    morph
    pulse
    quartz
    sandstone
    simplex
    sketchy
    slate
    solar
    spacelab
    superhero
    united
    vapor
    yeti
    zephyr

