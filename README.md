## README.md

This is the static html website code for https://marmalade.ai whcih automatically deploys to Netlify.

To install and run locally:  

    git clone --recurse-submodules https://github.com/craigfisk/marmalade.ai.git
    cd marmalade.ai  
    hugo server -D  
    // if you didn't include "--recurse-submodules" you will get error messages about missing theme components  
    // Now open "localhost:1313" in your web browser  

<<<<<<< HEAD
### History:
- As of 2019-8-13, there are a homepage and a problem page.  
- As of 2019-8-17, https://marmalade.ai is running on Netlify.
- As of 2020-5-25, switched to Themefisher navigator-hugo theme.

### Detailed update 2020-5-25


- Switched to Themefisher navigator-hugo theme from hugo-casper-two theme.
- This is a responsive, single-page theme.
- index.html lists the "partials" being used. Most are commented out.
- An embedded Youtube video was added from Pexels.com
- Got it to loop but not to autoplay. Made need to convert hero.html to using HTML5 iframe to get it to work. 
- The theme is installed as a submodule in git.
- For development, you run "hugo serve" in the project root directory and browse to localhost:1313 to see results.
- For deployment, you run "hugo" in the project root directory, git add ., git commit etc., git push origin master and the repo on Github automatically is used to replace what is running on Netlify.
- Key files in addition to index.html are config.toml, images are in static/content/images, layouts/partials includes hero.html, about.html, team.html are the 3 main layout files and they run entirely with content defined in config.toml. assets/css/style.css has at least one new class, title-class for the title.
- The content in the 3-part section on history is in data/en/about.yml.
- This theme is set up to be used as a multilingual site. All of that has been commented out and could be brought back in.
||||||| merged common ancestors
As of 2019-8-13, there are a homepage and a problem page.  
As of 2019-8-17, https://marmalade.ai is running on Netlify.
As of 2020-5-25, switched to Themefisher navigator-hugo theme.
=======
### History:
- As of 2019-8-13, there are a homepage and a problem page.  
- As of 2019-8-17, https://marmalade.ai is running on Netlify.
- As of 2020-5-25, switched to Themefisher navigator-hugo theme.

### Detailed update 2020-5-25


- Switched to Themefisher navigator-hugo theme from hugo-casper-two theme.
- This is a responsive, single-page theme.
- index.html lists the "partials" being used. Most are commented out.
- An embedded Youtube video was added from Pexels.com
- Got it to loop but not to autoplay. Made need to convert hero.html to using HTML5 iframe to get it to work. 
- The theme is installed as a submodule in git.
- For development, you run "hugo serve" in the project root directory and browse to localhost:1313 to see results.
- For deployment, you run "hugo" in the project root directory, git add ., git commit etc., git push origin master and the repo on Github automatically is used to replace what is running on Netlify.
- Key files in addition to index.html are config.toml, images are in static/content/images, layouts/partials includes hero.html, about.html, team.html are the 3 main layout files and they run entirely with content defined in config.toml. assets/css/style.css has at least one new class, title-class for the title.
- This theme is set up to be used as a multilingual site. All of that has been commented out and could be brought back in.
>>>>>>> 90af275ae39466e39769bf6ab7a13f3d525f0cac
