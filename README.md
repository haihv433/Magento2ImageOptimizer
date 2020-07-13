# Magento2ImageOptimizer

This module only for optimize your Magento 2 image library

In an assumption, your store deployed on Ubuntu and console running as root 

## Install

Put `bin` folder, or just copy a file `pagespeed_optimize_images` replace/ into your magento bin folder

The need to provide a right to execute is require
    
    chmod +x bin/pagespeed_optimize_images
    
## Usage
To do that, stay in Magento 2 Root, run:

	sudo bin/page_optimize_images.sh -t all -d pub/media


Available option:

`-t`: `jpegoptim`, `optipng` or `all`

`-d`: where script take effect

