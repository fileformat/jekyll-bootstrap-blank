# Jekyll Bootstrap Blank

All I wanted was a plain [Jekyll](https://jekyllrb.com/) template with [Bootstrap](http://getbootstrap.com/).  No extra themeing
system or plugins or other magic going on.  It should be so simple, yet it wasn't there.  So I made it.

## Things to change

 * replace occurences of `LATER` in any file
 * point `CNAME` to your domain name
 * replace `favicon.ico` and `favicon.svg` with your logo (and update the css in `/_includes/meta.html` if necessary)
 * remove `UNLICENSE.txt` and add the appropriate `LICENSE.txt` (or not!)
 * change the links in `/_includes/navbar.html` to reflect your website structure
 * update the `_data/credits.yaml` file to include the tech you are using

## Notes

I set the default layout to `default`, so if you have a page that has front matter but should not get the standard template,
you need to specify the `none` layout (see the `(robots.txt)[https://github.com/fileformat/jekyll-bootstrap-blank/blob/master/robots.txt]` file format an example).

All pages go into the `sitemap.xml` file unless they have `noindex: true` in the front matter.

## Credits

See the (credits page)[https://jekyll-bootstrap-blank.fileformat.info/]!

