# Ink

Ink is a minmal two-column theme for [Jekyll](http://jekyllrb.com) 

![Screenshot](https://s32.postimg.org/gdtp6pw1x/ink.png)

# Installation 

##### Setup on your local machine
 * Clone or download the repository
 * You should have [ruby](https://www.ruby-lang.org/en/) installed in your system
 * Install bundler which helps in specifying and installing dependencies of any Ruby project ```gem install bundler```
 * Go to the root of the repo and run this - ```bundle install```
 * Then - ```bundle exec jekyll serve```

##### Make it your own
 * Fork the repository
 * Follow the configuration step
 * Host your site/blog with **Ink**

# Configuration 
 * Change the following in ```_config.yml```
 ```
    name:               "Ink"
    description:        "A minimalistic jekyll theme for humans"
    url:                ""
    author:             "thinker3197"
    email:              "jhondoe@abc.com"
    gravatar_hash:      "205e460b479e2e5b48aec07710c08d50"
    twitter:            "jhondoe"
    email:              "jhondoe@abc.com"
    github:             "jhondoe"
    pinterest:          "jhondoe"
    linkedin:           "jhondoe"
    facebook:           "jhondoe"
    
 ```
 * Set the number of posts that appear in each page by changing the ```paginate``` option in ```_config.yml``` file. Default value is 5.
 * Add more navigation menus in the ```nav``` section in ```_config.yml```. 
 * Add your custom url in ```url``` option. Example : http://thinker3197.github.io/blog. Consult the ```gh-pages``` branch to see the basic setup for a blog.
 * Add your custom background by adding a custom background link in the ```background``` option in ```_config.yml```.
 
# Licensce

## BUILD INSTRUCTIONS
A. compile resume
    1. cd into markdown-resume
    2. type make
    3. cp resume.md into ink/
    4. (make sure any images you want are in images/ink/)
B. compile site
    1. cd ink/
    2. jekyll build
C. view site locally
    1. cd ink/_site/
    2. bundle exec jekyll serve
    3. point web browser at http://127.0.0.1:4000/
D. check in to github
    1. rm -rf danfinkel.github.io/*
    2. cp -r ink/_site/* danfinkel.github.io/
    3. git add danfinkel.github.io/
    4. git commit -m "checking in"
    5. git push
    6. navigate to github and ensure files checked in
    7. navigate to danfinkel.github.io/
    
    









    5. git push
    6. navigate to github and ensure files checked in
    7. navigate to danfinkel.github.io/

Open sourced under [MIT LICENSE](https://github.com/thinker3197/ink/blob/master/LICENSE) 





