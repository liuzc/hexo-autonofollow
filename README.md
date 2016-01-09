# hexo-autonofollow
Adds nofollow attribute to all external links in your hexo blog posts automatically.


## Features
* Add rel="external nofollow" to all external links, SEO friendly.
* Add target="_blank", Open external links in new window or tab

## Install

``` bash
$ npm install hexo-autonofollow --save
```

## Options
You can configure this plugin in  _config.yml.
```
nofollow:
	enable: true
	exclude:
    - exclude1.com
    - exclude2.com
```

- **enable** - Enable the plugin. Defaults to **false**.
- **exclude** - Exclude hostname
