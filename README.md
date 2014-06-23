# tenfourty/pressos

Hi There!

This is the repository for all of my public presentations, to see them (they are hosted on the OpenShift PaaS) just got to <http://pressos-runningonthe.rhcloud.com/>

***Feel free to copy anything I'm doing here but I would like to be given some credit/attribution and of course feedback too.***

Enjoy!

Jeremy Brown  [@tenfourty] [1]

[1]: http://twitter.com/tenfourty/ "@tenfourty"

### Running locally

Some reveal.js features, like external markdown and speaker notes, require that presentations run from a local web server. The following instructions will set up such a server as well as all of the development tasks needed to make edits to the reveal.js source code.

1. Install [Node.js](http://nodejs.org/)

2. Install [Grunt](http://gruntjs.com/getting-started#installing-the-cli)

4. Clone the this repository
```sh
$ git clone https://github.com/tenfourty/pressos.git
```

5. Navigate to the pressos/php folder
```sh
$ cd pressos/php
```

6. Install dependencies
```sh
$ npm install
```

7. Serve the presentation and monitor source files for changes
```sh
$ grunt serve
```

8. Open <http://localhost:8000> to view your presentation

You can change the port by using `grunt serve --port 8001`.

### Running on OpenShift

All of my presentations are hosted on OpenShift - you can see my version here:  <http://pressos-runningonthe.rhcloud.com/>

Here is how to do this for yourself.

TODO - instructions in here

### Howto use Travis CI to automatically build and push to OpenShift this repository

This is how my workflow looks, when I push to my GitHub repository then Travis CI automatically does a build and pushes and update to my application running on OpenShift. Nifty eh?!

TODO - instructions in here


<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons Licence" style="border-width:0" src="http://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" href="http://purl.org/dc/dcmitype/Text" property="dct:title" rel="dct:type">Jeremy Brown's Presentations</span> by <a xmlns:cc="http://creativecommons.org/ns#" href="http://pressos-runningonthe.rhcloud.com/" property="cc:attributionName" rel="cc:attributionURL">Jeremy Brown</a> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.<br />Based on a work at <a xmlns:dct="http://purl.org/dc/terms/" href="https://github.com/tenfourty/pressos" rel="dct:source">https://github.com/tenfourty/pressos</a>.<br />Permissions beyond the scope of this license may be available at <a xmlns:cc="http://creativecommons.org/ns#" href="mailto:jeremy@tenfourty.com" rel="cc:morePermissions">mailto:jeremy@tenfourty.com</a>.
