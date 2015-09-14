# Magento Module Composer Repository #

* The URL of original repo is [packages.firegento.com](http://packages.firegento.com/).
* Url of original github repo is https://github.com/magento-hackathon/composer-repository

#build

* create a folder for entire structure
* clone this repo in a sub-folder. So scripts can build their folder structure without issues
* First Initialize it by running the script
  * `php initSatisGenerator.php`
* run buildAndPush
  * `php buildAndPush.php`
  * Please note that you need push access to the repo.
  * You can fork this repo and change this line to use your fork
    * `script/initSatisGenerator.php:21`
    * `passthru("git clone git@github.com:zainengineer/composer-repository.git $magentoComposerRepositorySourceDir");`  
 
