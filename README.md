# Mongo PHP ext module for Puppet

Basic rough module to install MongoDB PHP extension (via pecl) and add it into php.ini

Equivalent to the shell commands
    
    sudo pecl install mongo
    cat 'extension=mongo.so' > "/etc/php5/conf.d/mongo.ini"

Feel free to fork and pull-request changes, or suggest alternatives. 
At the time of writing there is no separate puppet module able to do the above
    
