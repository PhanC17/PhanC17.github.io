# Introduction
This site is an e-portfolio showcasing my work experience and past projects. The e-portfolio was created using GitHub pages and Jekyll pages theme. This page serves as a tutorial on how to to create a similar e-portfolio.

**IMPORTANT: Any changes you make for the site needs to be commited to the repository before it can be viewed on the website. The easiest way to quickly edit the files is to clone the repository onto your personal device through GitHub Desktop. Commits can then be made in the desktop app before being pushed onto the branch.**

# Creating the Website
When creating a new repository for the website, name it your GitHub username with ".github.io" appended to the end. This allows GitHub to recognize the repository as a site directory and builds the page using the files within.  
`username -> username.github.io`


The first file that needs to be made is an "index.md", a markdown file. This file represents a page that can be accessed through the root url. Anything typed in this file will be the first thing visible on the page when anyone visits the url.

## More Pages
Pages are created through markdown files. These pages can be accessed by appending the name of the file to the end of the website name. Remember that the website is case-sensitive.  
```
index.md                    username.github.io/ 
another.md                  username.github.io/another
```
With multiple subpages, folders can be used to organize them. This will be reflected in the website including the name of the folder. The website effectively acts similar to a file explorer address, with it also being case-sensitive.
```
index.md                            username.github.io/
    |_subpage                       
        |_another.md                username.github.io/subpage/another
```
# Customizing the Website
The next step is to customize the appearance of the website. One of the easiest ways to do this would be to use a premade theme. GitHub Pages provides multiple themes using Jekyll to integrate them into the page.
## Adding the theme to the Repository
This site used the Minimal theme, which can be found [here](https://github.com/pages-themes/minimal). The project contains all the base files needed to apply the theme to your site.  
1. Download the project as a ZIP file.
2. Unzip the files into the folder that houses your repository.
     - This adds all the required files to integrate the theme into your website. Once these changes are commited, the website will take the appearance of the sample website, with the sample text as well.
## Personalization
3. Change the README.md and index.md files to apply them for your personal use. For my use, I changed the index.md to my resume, and the README.md to explain the site and add credit for the theme.
4. Go into the `_config.yml` to personalize the sidebar for yourself.
