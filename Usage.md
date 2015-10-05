# Introduction #

This page introduces the usage of SecureImage PHP Image Validator.


# Sample Code #

```
<?php
include("SecureImage.php");
$image=new SecureImage('8k2containsEXIF.jpg');
if($image->CheckIt())
        echo "Yeaah Dude! You can trust it";
else
        echo "Bad image file!";

?>
```