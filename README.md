# nodejitsu
Hello world, for node-jitsu

See the docs [https://github.com/nodejitsu/handbook#hiworld](https://github.com/nodejitsu/handbook)
and the [cheatsheet](http://cheatsheet.nodejitsu.com/)

## install tool

    sudo npm install jitsu -g
    jitsu help
    
    jitsu signup # requiers activation
    jitsu login # careful, your password goes into ~/.jitsuconf in cleartext
    
    jitsu apps list
    jitsu databases list
    jutsu databases create <couch|redis|mongo> <dbname>
    

# deploy
The first deploy will ask for a few qustions, the get stored in your package.json

    jitsu deploy 