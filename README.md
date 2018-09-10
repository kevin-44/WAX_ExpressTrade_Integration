<p align = "center">
	<img alt = "Header" src = "img/header.png">
</p>

In this tutorial, you will learn how to integrate [WAX ExpressTrade](https://blog.opskins.com/opskins-expresstrade) into your website using [Node.js](#nodejs) or [PHP](#php)!

#### Table of Contents

* [Node.js](#nodejs)
	* [Beginners](#beginners)
		* [Local Environment](#local-environment)
		* [Production Environment](#production-environment)
			* [Order/Create Your VPS](#ordercreate-your-vps)
			* [Log In & Prepare Your VPS](#log-in--prepare-your-vps)
* [PHP](#php)
	* [Beginners](#beginners-1)
		* [Local Environment](#local-environment-1)
		* [Production Environment](#production-environment-1)
			* [Order/Create Your VPS](#ordercreate-your-vps-1)
			* [Log In & Prepare Your VPS](#log-in--prepare-your-vps-1)

# Node.js

## Beginners

### Local Environment

### Production Environment

#### Order/Create Your VPS

#### Log In & Prepare Your VPS

# PHP

## Beginners

Before anything, you will need to install a **web server** and **PHP**. If you already know how to do this, skip to the [next step](#beginners-1).

### Local Environment

If you aren't interested in setting up an environment for local development, you can skip directly to [setting up a production environment](#production-environment-1) (preparing your website on a host) right off the bat.

A web server and PHP can be installed by many different means, although [XAMPP](https://www.apachefriends.org) is an all-in-one package that's incredibly easy to install and use; hence, it's a highly recommended option and you should definitely consider using it!

After installing XAMPP (or the above by any other mean), start **Apache** (the web server):

<img alt = "XAMPP - Start Apache (The Web Server)" src = "img/xampp_start_apache_server.png">

Any website you create should be placed in the `htdocs` folder where you installed XAMPP. You can access your websites at `http://localhost/some-website` via your browser, where `some-website` is the path to one of your websites.

> **Note**: The **web server** must be running for you to access your *unpublished* website. If you reboot your PC, you must open XAMPP and start it again.

### Production Environment

Hosting your website implies that you rent a **VPS** (*Virtual Private Server*) from a company of choice to keep it accessible 24/7. There are many companies you can rent a VPS from, although some may require that you submit a whitelist application beforehand (such as [OVH](https://www.ovh.com/world)). If you're looking for a decent VPS that's also quick to set up, [DigitalOcean](https://www.digitalocean.com) is an excellent option!

#### Order/Create Your VPS

Regardless of the company you decide to rent your VPS from, you must get it online with your **OS** (*Operating System*) of choice installed. **Ubuntu** is recommended for beginners.

<img alt = "DigitalOcean - Create Droplet" src = "img/digitalocean_create_droplet.png">

Typically after creating a VPS, its log in credentials are sent via email - have them ready because you'll need them in the next step!

<img alt = "DigitalOcean - Credentials Email" src = "img/digitalocean_credentials_email.png">

> **Note**: Hosting a website on a Windows server is possible; however, it isn't recommended for beginners - many network adjustments must be applied to prevent attacks by third parties.

#### Log In & Prepare Your VPS

You will need an **SSH client** in order to log into your VPS - [putty](https://www.chiark.greenend.org.uk/~sgtatham/putty/latest.html) is highly recommended!