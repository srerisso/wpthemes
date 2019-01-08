# WPThemes

## About
WP theme development. A personal project, starting in January 2019, to train myself in WP development.

### Trelis. Wordpress server in a local environment.


Right now, the first step is to install and configure [Trellis](https://roots.io/trellis/).

**How-To:** Install Trellis.

1. Install Trellis.

```
$ mkdir srerisso.com && cd srerisso.com

$ git clone --depth=1 git@github.com:roots/trellis.git && rm -rf trellis/.git
```

Install Bedrock into the _site_ directory.
```
$ composer create-project roots/bedrock site
```

2. Configure a WP site.

wordpress_sites.yml

3. Vagrant up.

```
$ cd trellis

$ vagrant up
```

After a change, it is safe to provision the VM again to apply changes:

```
$ vagrant reload --provision
```


## Sage. Theme development.

**How-To:** Theme development with [Sage](https://roots.io/sage/), Laravel and Laravel Blade template system.

```
$ composer create-project roots/sage <your-project-name>

$ cd <your-project-name>

$ yarn

```
