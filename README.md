# ia2web
Static site generation of iA Writer (and compatible) Markdown files.<br>
[View on GitHub](https://github.com/svandragt/ia2web)

![Screenshot](https://user-images.githubusercontent.com/594871/127234909-a06ddd05-f163-416e-8f51-b744d8cd2737.png)


## Setup

In the directory of markdown files:

```
# install
git clone https://github.com/svandragt/ia2web.git .export && cd .export && composer install

# start watcher
php ia2web.php
```

A new `html` folder containing a static website is created.

## Features

- Watches notes folders for content changes, generating html on the fly.
- Simple script, hack away.
- Handles `.md` and `.txt` notes.
