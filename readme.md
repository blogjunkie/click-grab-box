Click to Copy Grab Box makes it easy to generate code for your blog button. The plugin adds a widget to WordPress that will display a textarea with code for your readers to copy and paste into their blogs. The widget will even automatically generate the correct code for you. Simply will out the fields in the widget and click Save.

**Features**

* No coding knowledge required! Just fill in the fields and your blog button code will automatically be generated.
* Minimally styled so you can easily customize the widget to fit your theme. 
* Choose to display an optional message for instructions or a description of your blog button.


## Installation

1. Upload the plugin to the `/wp-content/plugins/` directory
1. Activate the plugin through the `Plugins` menu in WordPress
1. Go to `Appearance → Widgets` and drag the Grab Box widget into your sidebar.


## Frequently Asked Questions

**How can I style the widget to look better**  
Many themes allow you to add custom CSS. You can use this feature to customize the look of the widget.

If your theme doesn't offer custom CSS, you can try these plugins:

* [My Custom CSS](http://wordpress.org/extend/plugins/my-custom-css/)
* [Jetpack](http://jetpack.me) comes with a [custom CSS module](http://jetpack.me/support/custom-css/)

**What is my image URL?**  
Your image must first be uploaded to your blog or a picture hosting service like [Photobucket](http://photobucket.com). Find the direct link to the image (you will see a `.jpg`, `.gif` or `.png` at the end of the URL). 

**My image is sticking out past my sidebar**  
Add the following CSS to your theme.

	.click-grab-box-button img {
		max-width: 100%;
		height: auto;
	} 