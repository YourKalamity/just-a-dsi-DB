# just-a-dsi-DB
A JSON database containing names, links and GitHub repos for homebrew on the DSi. 
Created for use with lazy-dsi-file-downloader

Each title has:
- `title`, the name of the title
- `gitHub`, whether or not to download the latest from gitHub or use a predefined link (either `True` or `False`)
- `repo`, the gitHub repository it is from, if on gitHub (left blank if none)
- `extension`, what format the download link comes in, ie `.nds` `.zip` or `.7z`
- `author`, the creator of the title
- `link`, the link to download the title (if empty then use the latest from gitHub via api.github.com)

