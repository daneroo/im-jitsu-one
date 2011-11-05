# Hello nodejitsu
Hello world, for node-jitsu. It is deployed at [http://im-jitsu-one.nodejitsu.com/](http://im-jitsu-one.nodejitsu.com/)


I came back to nodejitsu after finding [hook.io](https://github.com/hookio/hook.io) and then [haibu](https://github.com/nodejitsu/haibu) which is built partly on top of the hook.io bus.

See the docs [https://github.com/nodejitsu/handbook](https://github.com/nodejitsu/handbook)
and the [cheatsheet](http://cheatsheet.nodejitsu.com/)

Other docs at [http://docs.nodejitsu.com/](http://docs.nodejitsu.com/)

Not yet available but comming soon [Admin Dashboard](http://develop.nodejitsu.com.)

## TODO

    Proper way to inject db credentials into app.

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