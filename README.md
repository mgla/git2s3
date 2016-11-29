# git2s3

## Installation

* Install necessary perl module 'JSON'. Debian: libjson-perl
* Install git
* Install s3cmd
 * For each bucket you want to use with git2s3, add a ~/.s3cfg.$bucketname  
   s3cmd configuration file
* Add a ~/.git2s3.json file
* Install git2s3 into your path


##ToDo

* Use API instead of S3cmd.
 * Also remove fixed filters

