Downloaded Clojure v1.7.0 stable from http://clojure.org/downloads

Forgot Clojure runs on the JVM. Downloaded Java SE Development Kit 8 update 65 from here: http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html
(Ick, Oracle)

REPL worked fine, but it wasn't immediately evident how to compile or execute a Clojure script outside of the REPL. This site http://www.braveclojure.com/getting-started/
recommended Leiningen for that purpose, so I downloaded it from here: http://leiningen-win-installer.djpowell.net/

Was able to create a new lein project with the following command (Note that Clojure really doesn't like capital letters for some reason):
lein new app helloworld

Then can run it by running the following in the new app directory created by lein:
lein run

Was also able to build it into a standalone JAR by running this in the app's directory:
lein uberjar


Certainly the most complicated setup I've done on this project so far. Doesn't really feel like Clojure cares about any development done outside of the command line lein seems really good though.