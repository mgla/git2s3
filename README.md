# git2s3

Simple tool to push contents of a git repository to S3 bucket(s) via CLI.

## Installation

* Install necessary perl module 'JSON'. Debian: libjson-perl
* Install git
* Install s3cmd
 * For each bucket you want to use with git2s3, add a ~/.s3cfg.$bucketname  
   s3cmd configuration file
* Add a .git2s3.json file to one of the following pathes (will be priorized in that order):
 * your git repository base
 * your current working directory
 * to ~/
* Install git2s3 into your path
