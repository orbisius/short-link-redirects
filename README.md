# short-link-redirects
collection of .htaccess rewrite rules that enable your WordPress site to use short links

Make sure you put the rules at the top of your existing .htaccess file.
If you have access to the vhost file it's even better to put them there for performance reasons.

This should be used on a site that runs WordPress.

The result would be that you can have this without an extra plugin.
This will redirect to a blog post/page with that id.

example.com/123

This is useful to track how many people have come from youtube
example.com/yt123

