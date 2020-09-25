# DOM Cloud Templates


These files are templates to install and host most common web frameworks to internet. 

[You can start deploy them now for free on DOM Cloud](https://portal.domcloud.id/start).

Available templates currently:

+ [WordPress](https://portal.domcloud.id/start?from=https://raw.githubusercontent.com/domcloud/dom-templates/master/wordpress.yml)
+ [Laravel](https://portal.domcloud.id/start?from=https://raw.githubusercontent.com/domcloud/dom-templates/master/laravel.yml)
+ [Django](https://portal.domcloud.id/start?from=https://raw.githubusercontent.com/domcloud/dom-templates/master/django.yml)
+ [Rails](https://portal.domcloud.id/start?from=https://raw.githubusercontent.com/domcloud/dom-templates/master/rails.yml)

You're free to submit PR about other popular frameworks.

## Script Spec

All install script templates uses YAML with following simple spec:

```yml
source: <source url>
directory: <directory to extract>
root: <webserver root>
features:
- list of features
commands:
- list of shell commands
```

All props there is optional, except source. Otherwise no install script is executed.

#### Source

This source url is full path to a ZIP somewhere in internet available for public, either starts from `http://` or `https://`. If it's not a ZIP file, it'll not get executed.

A special url format for fetching GitHub archives is available, using pattern `github://owner/repo#tag`. The `#tag` here is optional. Internally that GitHub URL expands to `https://github.com/owner/repo/archives/tags.zip`.

#### Directory

The name of directory inside the ZIP file to be extracted. If it's not provided, either it's guessing from `github://` URI or not moving files out of a directory at all.

#### Root

The webserver root to serve. By default it's `public_html`. Usually for modern frameworks you put the root in `public_html/public` so that your server scripts don't get exposed.

#### Features

List of features of hosts that you need. Valid values are: 

+ `mysql`, enable MySQL database feature 
+ `postgres`, enable Postgres database feature 
+ `ssl`, enable HTTPS and attempt to validate domain to Let's Encrypt.

Remember that in freedom plan, you're only allowed to create one database per host.

#### Commands

List of linux commands that you wish to execute just after extraction complete. Think like what commands you want to call after unzipping the source files using SSH. All commands here internally will be imploded with ` ; `, also it has common subtitution to let you modify config files using `sed -i`:

+ `${DOMAIN}` the domain name (without *http://* prefix)
+ `${USERNAME}` unix username (for host and database login)
+ `${PASSWORD}` unix password (for host and database login)
+ `${DATABASE}` database name

## Embed Link

You can use this link format: 

```https://portal.domcloud.id/start?from=<fileurl>```

where `<fileurl>` is URL to publicly accessible resource to YAML config. If that's file is in GitHub, you can use `https://raw.githubusercontent.com/owner/repo/master/configfile.yml`. Just remember to encode that URL so it can be imported properly.

## Limitation

The Freedom plan gives you free domain, 200 MB storage, 6 GB net data a year, and 5 minutes (of new and re-) deployment time, and unlimited renewal per host. Of course these limitation can be increased if you're enrolling a subcription.

DOM Cloud is not like Docker or Heroku, which is immutable and container-based. All deployment here are mutable, you can edit it futher or relauch your deployment under the same host. [More information here](https://github.com/domcloud/dom-portal).

