Caneda Website
==============
Caneda uses *jekyll* and *Github* as the project website system. *Github* hosts the website, making it fully accesible and easy to find, and *jekyll* is the website html static generator used by our site. *Github* supports webhooks so the site gets automatically built when you commit code.

Among the main features of *Github* sites, you can find: 
  * GitHub integration
  * Auto-updating
  * Versioning of the site using git

You can find Caneda's website online, generated automatically from this repository at:

http://www.caneda.org


Adding Documentation
--------------------
To add new documents, simply create a new ``webpage.md`` file (or edit an existing one) and push your changes to the repository. The only requirement to your new file is to include a ``layout`` section at the beginning of the file, for example:

    ---
    layout: page
    title: About
    permalink: /about/
    ---

To review your changes before commiting, run the following command from a terminal:

``$ jekyll serve``

And direct your favorite browser to http://localhost:4000.

