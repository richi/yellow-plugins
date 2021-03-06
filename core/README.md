Core plugin 0.6.9
=================
Core functionality for your website.

## How do I install this?

1. [Download and install Yellow](https://github.com/datenstrom/yellow/).
2. [Download plugin](https://github.com/datenstrom/yellow-plugins/raw/master/zip/core.zip). If you are using Safari, right click and select 'Download file as'.
3. Copy `core.zip` into your `system/plugins` folder.

Do not delete this plugin, it's always required.

## How to use the core?

The plugin provides the core functionality for your website. It takes care of requests from the web browser and access to the file system. You can use the [web interface](https://github.com/datenstrom/yellow-plugins/tree/master/webinterface) or the [command line](https://github.com/datenstrom/yellow-plugins/tree/master/commandline) to show software version and updates. To show more information about your website add a `[yellow]` shortcut to a page. See example below.

## How to configure the core?

The following settings can be configured in file `system/config/config.ini`:

`Sitename` = name of the website  
`Author` = webmaster's name  
`Email` = webmaster's email  
`Language` = default language  
`Timezone` = default timezone  
`Theme` = default theme  

These are the most important settings. For a complete list see [configuration file](https://github.com/datenstrom/yellow/blob/master/system/config/config.ini).

## Example

Content file with Yellow version:

```
---
Title: Example page
---
This website is made with [yellow].
```

Content file with Yellow version, including plugins and themes:

```
---
Title: Example page
---
This website is made with Yellow:

[yellow version]
```

## Developer

David Fehrmann and Mark Seuffert
