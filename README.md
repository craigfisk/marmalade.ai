This is the static html website code for https://marmalade.ai whcih automatically deploys to Netlify.

To install and run locally:  

    git clone --recurse-submodules https://github.com/craigfisk/marmalade.ai.git
    cd marmalade.ai  
    hugo server -D  
    // if you didn't include "--recurse-submodules" you will get error messages about missing theme components  
    // Now open "localhost:1313" in your web browser  

As of 2019-8-13, there are a homepage and a problem page.  
As of 2019-8-17, https://marmalade.ai is running on Netlify.
As of 2020-5-25, switched to Themefisher navigator-hugo theme.
