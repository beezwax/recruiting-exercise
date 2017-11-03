# Beezwax Recruiting Exercise Dev Environment

This repo presents a base Rails 5 install for the standard Beezwax recruiting exercise so that you can spend your time writing code and not configuring an environment.

Clone like so (replacing Your-Name):

    git clone git@github.com:beezwax/recruiting-exercise.git beezwax-exercise && cd beezwax-exercise && git checkout -b Your-Name && bundle install

It was created like this:

    rails new beezwax-recruiting-exercise \
    && cd beezwax-recruiting-exercise \
    && echo 'gem "haml-rails", "~> 1.0"' >> Gemfile \
    && echo 'gem "rspec-rails"' >> Gemfile \
    && bundle install \
    && rails generate rspec:install

As you can see, both MiniTest and Rspec are available, and it includes haml.

If you prefer other configurations, you are 100% free to build your own environment and not use this repo.

At the scheduled time of your exercise, you will receive instructions on what to build.

If you *do* use this repo, you can simply submit your branch as a pull request. Otherwise, when you're done, please zip up your solution and return it to us.

If you *do NOT* use gmail, you can email the archive to careers@beezwax.net.

Gmail now blocks attachments with js files (as well as compressed archives that include js files). Since we ask you not to put your solution in a public repository, the best way to return it would be to make the archive available via Google Drive, Dropbox, or similar, and send us the link.

We'll send your solution around the team for review; you should hear back from us within a day or two.
