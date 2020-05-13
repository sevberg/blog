# Installation steps
1. Create 'blog' environment
    ```bash
    $ conda create --file environment.yml
    ```

2. Activate 'blog' environment
    ```bash
    $ source activate blog
    ```

3.  Initialize pelican application
    ```bash
    $ pelican-quickstart 

    > Where do you want to create your new web site? [.] 
    > What will be the title of this web site? sevberg
    > Who will be the author of this web site? D. Severin Ryberg
    > What will be the default language of this web site? [en] 
    > Do you want to specify a URL prefix? e.g., https://example.com   (Y/n) y
    > What is your URL prefix? (see above example; no trailing slash) https://sevberg.dev
    > Do you want to enable article pagination? (Y/n) Y
    > How many articles per page do you want? [10] 
    > What is your time zone? [Europe/Paris] Europe/Berlin
    > Do you want to generate a tasks.py/Makefile to automate generation and publishing? (Y/n) Y
    > Do you want to upload your website using FTP? (y/N) N
    > Do you want to upload your website using SSH? (y/N) N
    > Do you want to upload your website using Dropbox? (y/N) N
    > Do you want to upload your website using S3? (y/N) N
    > Do you want to upload your website using Rackspace Cloud Files? (y/N) N
    > Do you want to upload your website using GitHub Pages? (y/N) N

    ```