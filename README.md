# MPA Human Uses &middot; [![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg?style=flat-square)](https://github.com/your/your-project/blob/master/LICENSE) & OST Data Viewer

Project website for Marine Protected Areas (MPA) Human Uses. The project is establishing a statewide baseline and long-term MPA monitoring program for commercial and commercial passenger fishing vessel (CPFV) fisheries in the State of California. View data MPA Human Uses data.

## Installing / Getting started

Steps:  
  1. Download Wordpress to your project folder
  2. If you don't already have it install MAMP or another Apache, MySQL, and PHP stack
  3. Create a new host in MAMP `mpa.local`
  4. Choose your downloaded wordpress directory as the document root
  5. Create a database for wordpress and name it `mpa_human_uses_db`
  6. in the wordpress directory find the file `wp-config-sample.php`
  7. Duplicate `wp-config-sample.php` and name the new file `wp-config.php`
  8. open `wp-config.php` in a text editor
  9. update `define( 'DB_NAME', '' );` to `define( 'DB_NAME', 'mpa_human_uses_db' );`
  10. update `define( 'DB_USER', '' );` and add your DB username, likely `define( 'DB_USER', 'root' );`
  11. update `define( 'DB_PASSWORD', '');` by adding your DB password
  12. save the file
  13. launch http://mpa.local or https://mpa.local in your browser and you should see the Wordpress setup guide
  14. follow the wordpress setup guide
  15. login to wordpress after setup
  16. Download the DIVI wordpress theme and add it to `wp-content/themes/`
  17. clone this repo in the wordpress directory under `wp-content/themes/`

```shell
cd wordpress/wp-content/themes
git clone https://github.com/Ecotrust/mpa-ca.git
cd mpa-human-uses
```


## Developing

...


### Built With
  * Wordpress
  * CA web template


### Prerequisites
  * Git
  * MAMP stack


## Licensing

MIT
