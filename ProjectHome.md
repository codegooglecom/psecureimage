SecureImage is a image validator that can be used for validating image files on upload systems (such as photo galleries,forums,etc ..) against the threads for XSS issues with IE and LFI attacks.

For Internet Explorer; you can succesfully launch XSS attacks with malformed image files because of it's mime-type detection algorithm.

Also the image files can contain some server-side payloads that can be used on exploiting of LFI vulnerabilities.

This image validator class; first checks for if the image is valid, after that it cleans the EXIF section.

It uses GD for these image operations and also doesn't leave the GD banner at the EXIF.

![http://www.webguvenligi.org/wp-content/themes/ocean-mist-10/images/mainpic.jpg](http://www.webguvenligi.org/wp-content/themes/ocean-mist-10/images/mainpic.jpg)