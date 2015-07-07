# reagent-hello

Every code sample from the [Reagent Project](http://reagent-project.github.io), rendered inside a single [Reagent](https://github.com/holmsand/reagent) component, using [figwheel](https://github.com/bhauman/lein-figwheel).

The project was initially generated using the [Leiningen](http://leiningen.org/) generator:

```bash
lein new figwheel -- --reagent
```

## Setup

To get an interactive development environment run:

    lein figwheel

and open your browser at [localhost:3449](http://localhost:3449/).
This will auto compile and send all changes to the browser without the
need to reload. After the compilation process is complete, you will
get a Browser Connected REPL. An easy way to try it is:

    (js/alert "Am I connected?")

and you should see an alert in the browser window.

To clean all compiled files:

    lein clean

To create a production build run:

    lein cljsbuild once min

And open your browser in `resources/public/index.html`. You will not
get live reloading, nor a REPL. 

## License

Copyright © 2014 James Martin

Distributed under the Eclipse Public License either version 1.0 or (at your option) any later version.
