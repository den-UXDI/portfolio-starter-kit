# Portfolio Starter Kit

## Objectives

- Build a cool portfolio
- Get hosting and a custom domain name
- Host our cool portfolio on our custom Domain Name

## Repo

First thing's first - create a new repo for your project. Initialize it with a readme and an index.html file that gives a simple 'hello world':

```html
	<!DOCTYPE html>
	<html>
	<head>
		<title>My Portfolio</title>
	</head>
	<body>
		<h1>Hello World!</h1>
	</body>
	</html>
```

This will be important as we set up hosting - we'll want some sort of visual indication that our setup is working.

There's a sample index.html file in this repo, but make sure your portfolio is not in a fork of this repo - make it yourself, so that future employers can see that this project is ALL YOU!

## Hosting

Let's start with the more technical side of this project - getting hosting and a domain name. 

Hosting, in a nutshell, is renting a folder on a server for your project to live in. Much like renting an apartment, quality and cost can varry wildly. Here's a few suggestions for hosting

- [Dreamhost](https://www.dreamhost.com/) - Standard fair hosting service. around $25/mo. Handles domain, email, and other common services for you. Almost unlimited storage.
- [Amazon Web Services](https://aws.amazon.com/) - Cheap and scalable - only pay for what you use (could be as low as $1-3). No frills. 
- [Heroku](https://heroku.com/) Cloud app hosting - Probably overkill for what you need, but good if you want to scale to hosting full apps. Price tiers based on usage, from free - $500/mo.

- Never use GoDaddy. Never use GoDaddy.

Each hosting service will have its own way of handling how your files are stored and updated. You'll need to read their documentation to understand how that works.

## Domain Names (DNS)

Domain names are NOT technically part of your hosting package. Once your website has its metaphorical appartment, it can only be reached by an IP number. For instance, to get to Google without using its Domain name, you can go to 8.8.8.8.

Many services like Dreamhost will sell you a domain name as part of your hosting package. This is your best option, as its often difficult to coordinate the ownership of your DNS. If the hosting you pick doesn't, make sure you buy your domain from a reputable company, like [Google](https://domains.google/#/). There is a [very real blackmarket for Domain Names](https://gimletmedia.com/episode/7-this-website-is-for-sale/) that you will want to avoid.

### Top Level Domains

Your website can end with a lot more than .com - here's a complete rundown:

- .com - standard, totally fine

- .co - cool and new

- .___ (new top level domains): http://data.iana.org/TLD/tlds-alpha-by-domain.txt - great if relevant

- .net, .biz - NEVER.

## Site Architecture

While we've learned a lot of fancy tools to make full-stack sites, you probably won't need any of that in order to make a great portfolio site. My suggestion for your portfolio is:

- root
	- index.html 
	- css
		- bootstrap.css
		- main.css
	- js
		- main.js







