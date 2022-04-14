# Erlend Thune

You can read more about me on my [linkedIn profile](https://www.linkedin.com/in/erlendthune/). 

See below for some of the work I've done privately and professionaly.


# IOS apps

You can install my apps from [my profile on IOS app store](https://apps.apple.com/no/developer/erlend-thune/id673691109).

[Cheese heaven](https://github.com/erlendthune/xcode-cheeseheaven) is an app where I learnt how to use the new sprite kit in Xcode. Help the mouse jump
over the perils and escape from the deep caves. If you manage to do this you will rejoin with you friend in cheese heaven! All images and sounds 
have public licenses and the mouse trap photo is taken by me :) Link to 

[Corrate](https://github.com/erlendthune/xcode-corrate) connects to your bluetooth heart rate device and tells you what your pulse is with sound as often as you like. 
I made this app inspired by six-time Ironman Mark Allen and [what he wrote]( http://www.triathlontrainingarticles.com/Base.html) about heart rate training:

"You can either try to race with an engine the size of a lawnmower, or you can build your engine up with a good base so that you are racing 
with a huge-turbo charged jet engine." 

The app has an [accompanying facebook page](https://www.facebook.com/HeartRateTraining) where I've collected some articles about heart rate training.

[Polpriser](https://github.com/erlendthune/xcode-polpriser) contains a sqlite3 database with all the products and prices in the Norwegian vinmonopolet.
I made it back in the times when GSM data was costly and you wanted to check the prices on wine etc. in tax free shops to see if they were a bargain.
To create the database, I made [ruby scripts](https://github.com/erlendthune/polpriser) to scan vinmonopolets web pages. Vinmonopolet has later
provided an API to access their products, but I've found that the API does not contain all the products. 

# Work related projects

I use [another profile](https://github.com/etsikt) for work related projects. 

## Canvas LMS custom frontend

I maintain the GUI for [Norways largest e-learning portal](https://kompetanse.udir.no) 
in [this repository](https://github.com/matematikk-mooc/frontend). 

## LTI

To expand the functionality of the GUI above, I first made some initial prototypes of an LTI module through these projects:

- [KPAS-LTI](https://github.com/etsikt/KPAS-LTI)
- [KPAS](https://github.com/matematikk-mooc/KPAS)

These were later developed further into [kpas-api](https://github.com/matematikk-mooc/kpas-api) by external developers, and is now maintained by me.

## Interactive video transcripts

Inspired by the interactive video transcripts used in the [Coursera platform](https://www.coursera.org/), I made javascript code to do the same for
YouTube videos. The code was later improved by [DMR-coding](https://github.com/DMR-coding), and I am proud to 
be [accredited for my work there.](https://github.com/DMR-coding/youtube-dynamic-transcripts#acknowledgements)

I've later developed the same functionality for Vimeo. That solutino requires both backend and frontend code, and currently 
the backend code is only available 
in the KPAS-API describe above, not as an independent module. An example of how the interactive vimeo transcripts work 
[can be seen here](https://www.erlendthune.com/vimeo/vimeo.html). Notice that you can click anywhere in the interactive transcript, to make
the video start playing from the corresponding timestamp.

## QTI converter
[QTI](https://www.imsglobal.org/question/index.html) is as standard for exchanging digital questions. I wrote a PHP script
to convert questions from excel to QTI, which can be [accessed here](https://www.erlendthune.com/xborrow/canvastabtoqti.php). 
I got a request from an eployee of the [Americana university in Paraguay](https://www.americana.edu.py/) to reuse the code,
which I then [provided here](https://github.com/etsikt/canvastabtoqti).


