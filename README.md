# Personal Homepage
- This is a personal home page for Ambition Chen (Chen Xuan)

## Running this repo locally

- Install environment:
  1. Install Ruby with `sudo apt install ruby-dev ruby-bundler`
  2. You may need to change the path of bundle install: `bundle config path ./bundle_packages`
  3. Install needed Ruby packages by running `bundle install`.
  4. Re-run the previous command if you ever add new plugins.
  5. Start the site by running bundle exec `jekyll serve --open-url --livereload --trace`.
  6. Re-run the previous command if you make changes to _config.yaml.

- Run cite process:
  1. Install Python 3 (with PIP).
  2. Install virtual environment for Python `pip install virtualenv`.
  3. Create and enter the virtual environment `virtualenv fintech && source fintech/bin/activate`.
  4. Install needed Python packages by running `python -m pip install --upgrade --requirement ./_cite/requirements.txt`.
  5. Generate citations by running `python ./_cite/cite.py`.
  6. Re-run the previous command when you make changes to your input sources and metasources.

Visit **[chenxuan.space](https://chenxuan.space)** 🚀

_Built with [academicpages.github.io](https://github.com/academicpages/academicpages.github.io)_
