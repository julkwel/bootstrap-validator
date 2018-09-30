# bootstrap-validator
Issues of bootstrap validator, scroll in errors fields after page loading

** Bootstrap validator not scrolling page in errors fields after loading **

* This is how I fix it to scroll in errors fields after page is loading but you don't need that if page is not load *

$('html, body').animate({
   scrollTop: $('.has-error').offset().top - 10
 }, 'slow');

