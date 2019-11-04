# http://team.dreamspace.academy

## Setup repo
- `git submodule update --init`

## Pull latest versions all submodules
- `git submodule foreach git pull origin master`

## Create Website
- `git submodule add https://github.com/git_username/reponame.git user_folder_name`
- `git add . && git commit -m "Add user_folder_name website" && git push`
- `cd path/to/araCloud && fly remote-setup-website:team.dreamspace.academy`
