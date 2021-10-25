This a static site built using Jekyll and was published to Stanford's Domains hosting at https://blacklivesmatter.stanford.edu/

The credentials for FTP+SSL are in Clickup at https://app.clickup.com/t/1m3b3r0

Repo for the site is at: https://github.com/brightplum/stanford-blm/

# Install

This site built using Jekyll, ruby version 2.6.3: https://jekyllrb.com/

- Follow the Ruby and Jekyll installation instructions at https://jekyllrb.com/docs/installation/macos/
    - I recommend using `rbenv` to switch ruby versions
- Clone the site
- Run `bundle install` to install all gems

# Build and Compile

- To build and compile locally, run `bundle exec jekyll serve`
    - This will create a small webserver locally where you can access the site at `http://127.0.0.1:4000/`
- To compile before uploading via FTP+SSL, run `bundle exec jekyll build`
- All files are in the `_site` directory, which is excluded via `.gitignore`

# Theme Customizations

- Make customizations in `css/custom.css`
