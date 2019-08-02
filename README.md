# BAAAHS Central

A new website for your favorite sheep. Based on our now standardized development language [Kotlin].

This is really basic at the moment, you might even consider it a bit of a placeholder. However because we're printing instructions on inventory sheets that are going in bins right now immediately for all the new [sparklemotion] hardware and cabling we need to have a little something out there on the internets.

### Versions

If you change the version number in `build.gradle` you are also going to have to manually update name of the jar file that Heroku tries to run in the `Procfile`

## Starting the App

You should be able to just run it from IntelliJ IDEA - our standard IDE. Because this is a heroku app from the command line you should also be able to run

    heroku local
    
and have the app successfully startup. As we add a database connection this will get more complicated.


[Kotlin]: https://kotlinlang.org 
[sparklemotion]: https://github.com/baaahs/sparklemotion
