## README.md

This is the static html website code for https://marmalade.ai which automatically deploys to Netlify when pushed to Github.

To install and run locally:  

    git clone --recurse-submodules https://github.com/craigfisk/marmalade.ai.git
    cd marmalade.ai  
    hugo server -D  
    // if you didn't include "--recurse-submodules" you will get error messages about missing theme components  
    // Now open "localhost:1313" in your web browser  

### History:
- As of 2019-8-13, there are a homepage and a problem page.  
- As of 2019-8-17, https://marmalade.ai is running on Netlify.
- As of 2020-7-25, switched to Themefisher navigator-hugo theme from hugo-casper-two theme.

### Detail:
- Switched to Themefisher navigator-hugo theme from hugo-casper-two theme.
- This is a responsive, single-page theme.
- index.html lists the "partials" being used. Most are commented out.
- An embedded Youtube video was added from Pexels.com
- Video does not autoplay. May need to convert hero.html to using HTML5 iframe to get it to work. 
- The theme is installed as a submodule in git.
- For development, run "hugo server" in the project root directory and browse to localhost:1313 to see results.
- For deployment, assuming Github and Netlify accounts and configuration, then run "hugo" in the project root directory, which generates all the files in "public," then git add ., git commit etc., git push origin master and the repo on Github automatically replaces what is running on Netlify (may take 1-2 minutes; hit "refresh").
- Key files and directories: index.html, config.toml, static/content/images, data/en/*.yml, layouts/partials (includes hero.html, about.html, team.html, which are the 3 main layout files and they run entirely with content defined in config.toml), assets/css/style.css has at least one new class, title-class for the title.
- This theme is meant to be used in a multilingual site. All of that has been commented out and could be brought back in.
- Color scheme: orange splat logo: #ff7f00; "Marmalade AI" color: #fa5b46
