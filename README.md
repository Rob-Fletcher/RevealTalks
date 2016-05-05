#RevealTalks

All talks and slides written with Reveal.js will live in here. To make setting
CSS paths easier there will only be one folder deep and the table of contents
found here will help to navigate them.

The [template](template.html) file is a base template to be used for writing
new talks. It needs a lot of work.
***
##May 2016
Made new template using [pug(jade)](http://jade-lang.com/). To use this you must have installed [Node.js](https://nodejs.org/en/) and
the Node Package Manager (npm). You can then install pug with
    npm install pug-cli --global
This will allow you to render the pug templates into HTML. An example template can be found [here](Diphoton/2016/May/TalkExample.pug).
This automatically includes the layout and all you need to add is a `section` element for each slide you want to create.
You can then compile this template into HTML. In the directory containing the template run,
    pug TalkExample.pug -P
This will generate *TalkExample.html* in the same folder. This file will have all header and script includes needed as well as all of
your slide content.

Of course you are also free to write in plain HTML using the HTML template provided [here](Diphoton/DiphotonTemplate.html)

Egamma
=================================
2015
------
   - May
    + [Template](egamma/template.html)
   - April
    + [Release Comparisons](egamma/release_comparison.html)
   - June
    + [Finalize Release comparison](egamma/tracking_comparison.html)
        This talk will be given at egamma Tag and Probe Monday June 8th.
        It finalizes some of our studies on Rel 19 and Rel 20 comparisons.

Di-Photon
=================================
2016
------
   - May
     + [Template](Diphoton/jadeTemplates.jade)
     + [Group Talk, May 10](Diphoton/2016/May/GroupTalk.pug)
