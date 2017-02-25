# Redbrick-hugo

A theme for hugo

## Installation

```
$ cd themes
$ git clone git@github.com:redbrick/redbrick-hugo.git
$ cp -r redbrick-hugo/exampleSite/* ..
```

## Creating your first site

To generate your first site you can type the command:

```
$ hugo new site ~/my-website
```

Jump into your new site and have a look around at the files

```
$ cd ~/my-website
$ ls -F
```

Open up the <code>config.yaml</code> file to change the configuration of your website

```
$ nano config.yaml
```

## Changing pictures

To get started you will want to add your own picutres for your avatar, banner and about photos. To change these you will need to add these to your <code>/static/img/</code> folder.

* avatar.jpg
* banner.jpg
* about.jpg

## Building the Site

To build your site we type the command

```
$ hugo
```

This will output all the code into the <code>public</code> folder.

*Note:* Hugo can be weird if you don't delete your public before you generate everytime

*Warning*: rm -r is sometimes dangerous. Don't run in sudo unless you know what you are doing

```
$ rm -r public
```

This will _perminantly_ delete the public folder

## Looking at the site locally

If you wanna look at your site before you go and deplot it (recomended)

```
$ hugo server --bind=0.0.0.0 --baseUrl=http://localhost/ -D -F
```

This will generate a site on localhost:2323
