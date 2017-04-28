# _Cipher_

#### A Drupal web site that encrypts a phrase with the caesar cipher.

#### By Dan Lauby

## Description

This program allows users to enter a phrase and see the encrypted result.

## Planning

1. Configuration/dependencies
  * Drupal (7.54)
  * MySQL

  * 2. Application Specifications

    | Behavior | Input | Output |
    |----------|-------|--------|
    |Enter a shift value|2|a=0 -> a=2 or a=-2|
    |Enter a direction|'right'|a=0 -> a=2|
    |Enter a phrase|'Hello'|'Lgnnr'|

3. Integration
  * cipher custom module
    * custom display-answer page

## Setup/Installation Requirements

* Clone [cipher](https://github.com/danlauby/cipher) repository
* Download [Drupal 7.5.4](https://www.drupal.org/project/drupal)
  * Create MySQL database with 'cipher' as database name, password, user name and password
  * Run 'git init' in root directory
  * Run 'rm .gitignore'
  * Run 'cp sites/default/default.settings.php sites/default/settings.php'
  * Run 'chmod -R a+w sites/default'

## Known Bugs

None known.

## Support and contact details

Feel free to contact [Dan Lauby](dmlauby@gmail.com) with any questions.

## Technologies Used

* PHP
* Drupal
* MySQL

### License

Copyright (c) 2017 Dan Lauby
