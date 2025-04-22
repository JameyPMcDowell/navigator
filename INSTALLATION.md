I chose to make open-webui a submodule of the repo so i could more easily add tools/functionality as I go.

To repro, run these steps in sh:

# Add Open WebUI as a submodule
git submodule add https://github.com/open-webui/open-webui.git

# Commit everything
git add .
git commit -m "Initial commit with Open WebUI as submodule"