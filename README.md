Source for [brucebot.com](http://brucebot.com) , a Personal blog about Robotics Automation.

##Usage


###instagram/likedphoto

Set your own instagrame **access_token** in */instagram/instagram.php* and */likedphoto/
instagrame.php*.

`$access_token='Your token';`

###Rake deploy

If you want to do *rake deploy* as I do, add your own remote site info to **Rakefile**

`system "jekyll --rdiscount && rsync -avz --progress --delete _site/ XXX@XXX.com:/home/jekyll/ "`

--EOF--