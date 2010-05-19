CodeIgniter internationalization (i18n) library
===============================================

Originally by [Jérôme Jaglale](http://maestric.com/doc/php/codeigniter_i18n).

Fork by MetaStudio has the following features:

* Can use standalone hostnames (not just URI segments) to determine current language

Documentation
-------------

The original documentation is maintained by creator at [http://maestric.com/doc/php/codeigniter_i18n](http://maestric.com/doc/php/codeigniter_i18n).

Use hostnames
-------------

1. Add into your system/application/config/config.php lines identifying base URL for your
translation sites:

<code>
	$config['base_url_ru'] = "http://metastudio.ru/";
	$config['base_url_en'] = "http://metastudiohq.com/";
</code>

2. Enable the host mode in MY_Language.php:

	var $host_mode = true;

3. Enjoy 8)