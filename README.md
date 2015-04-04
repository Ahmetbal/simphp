# Introduction #

The simphp download does not come with a file called "readme". This page serves the purpose of the README file.

# Details #

### Installation ###
  1. Download the simphp file from the downloads section.
  1. Open the PHP file and edit the fields inside the CONFIG section.
  1. Upload the file to your web server.

### Usage ###
First off, note that simPHP stats can only be displayed on PHP-enabled webpages (with .php ext).

There are two simple lines of code that you need to display your views.

This first line should be placed as close to the top of the page as possible.

```
<?php include("path/to/simphp.php"); ?>
```

> Replace "path/to/simphp.php" with the relative or absolute path to the simphp.php from the webpage.
> If you don't know the absolute path to the simphp.php file, visit the file directly in your browser, placing "?display=true" at the end (minus quotes). For example:

> `http://example.com/simphp.php?display=true`


This line of code should be placed where you want the information to be displayed.
Note: Place this line inside your own tags. No tags are displayed with this line, unless specified in the CONFIG section.

```
<?php echo $info; ?>
```

> Example:
> `<p class="hits"><?php echo $info; ?></p>`

### Notes ###
  * The stats can be displayed on the simphp.php page, if the option is set in config.