Category Featured Images
------------------------
A Wordpress plugin that allows to set a featured image for each category.
Posts without a featured image set will show the category's featured image instead.
Featured images usually are placed by the theme in the single post page, in the latest posts page, etc.
But can also be shown using the shortcode [cfi_featured_image] or the PHP function cfi_featured_image()

Shortcode/PHP function optional arguments:
- 'size': 'thumbnail', 'medium', 'large', 'full'
- 'class': class of the image tag
- 'alt': alternative text of the image tag
- 'title': title of the image tag

Shortcode example: [cfi_featured_image size="large" title="This is a test..." class="my-image" alt="My image"]

Function example 1: cfi_featured_image( array( 'size' => 'large', 'title' => 'This is a test...', 'class' => 'my-image', 'alt' => 'My image' ) );

Function example 2: cfi_featured_image_url( array( 'size' => 'large' ) );

* * *

##### USAGE

 - Install and activate the plugin
 - Go in Posts \ Categories
 - Edit a category
 - Set the category featured image

* * *

![Screenshot](http://github.com/blocknotes/wordpress_category_featured_images/raw/master/screenshot.png)
