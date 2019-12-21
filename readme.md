CSS Minifier
============

Lightweight command line tool that utilises the great work of [cssminifier.com](https://cssminifier.com/), to minify `css` files.

### Installation

Add a `cssmin` script to your PATH, replacing _x.y.z_ with version.

```
# *nix shell script
java -jar /path/to/cssmin-x.y.z.jar "$@"

# windows batch file
@java -jar /path/to/cssmin-x.y.z.jar %*
```

### Usage

You can minify single files or entire directories and optionally specifiy an alternative output directory.

```
$ cssmin src/my_file.css
# Creates my_file.min.css in the src directory

$ cssmin src/my_file.css out
# Creates my_file.min.css in the out directory

$ cssmin src out
# Minifies all files in src and puts results in out

$ cssmin src out -r
# Same as before including subdirectories
```

### See Also

 - [JavaScript Minifer](https://github.com/CraicOverflow89/JavaScript-Minifier)