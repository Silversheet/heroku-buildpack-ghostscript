# Heroku Buildpack for Ghostscript

Installs Ghostscript 9.50 (default) or a custom version defined in Heroku ENV on Heroku

## Install

    $ cd /path/to/your-app
    $ heroku buildpacks:add https://github.com/Silversheet/heroku-buildpack-ghostscript
    
    # Push changes to deploy
    $ git push

    # This version of ghostscript will end up deployed at /app/vendor/ghostscript/bin/gs
    
