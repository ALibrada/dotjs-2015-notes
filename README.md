# dotJS 2015

It's always a pleasure to come to Paris and enjoy a dotConference, I was here last year and when I went out of the conference I just wanted to come back.

Well, they have done it even better and with even more people. I am really happy about the trip, the conference, the people and everything we learned.

## Christoph Porteneuve
### Modern Async.js [(Slides)](http://tdd.github.io/dotjs-async)

Opening talks so early in the morning have to be impressive because we, as listeners, are not still on the learning mode or listening phase. Well, this talk was indeed impressive.

At the beginning of the talk I was thinking that I already knew that stuff but after just a little while I realize the focus that Christoph was intending to show.

I really appreciated how he started by just talking about the main problem and the solutions that have been proposed during the time. We went through the solutions critically showing their pros and cons in a way that shows, we can use either one or the other depending on our different use-cases.

In my opinion, the part where he was using promises and generators was pretty good, difficult to understand and apply but anyway really interesting.

## Mathias Buus  
### Hyperdrive: p2p hash sharing tool [(Slides)](https://github.com/mafintosh/slides/blob/gh-pages/dotjs-2015/README.md)

This talk was not really about javascript but indeed was about an idea Mathias had implemented in JS. The hash-chunking and the merkle tree had really good points. Definitely using the idea of chunking files in the way that Git does with text files into any type of file is really promising and impressive.

The implementation of this idea is at least worth looking.

## Samuel Saccone   
### Dealing with garbage [(Slides)](https://docs.google.com/presentation/d/1uom69F6NGURHhrox1Ma50NW1nOKqdxRr0dKDNENwi6Y/)

Samuel was specially funny during this talk and made us laugh a lot. He made memory profiling really easy and fun looking even though most of the times isn't.

After explaining the whole process of memory profiling, he introduced another idea. Including this techniques into our Continuous Integration Systems with drool in order to prevent fixed memory issues to happen again without us realizing it.

## Rebecca Murphy
### HTTP/2 is here, now let's make it easy [(Slides)](https://speakerdeck.com/rmurphey/2-is-here-now-lets-make-it-easy)   

My favorite talk along the one from Eric Schoffstall. I was really waiting for this topic, I have learned a lot about it at work and this topic have in some way woken me up. There are a lot of "hacks" or workarounds in how to load content in the web just to overcome some HTTP/1 problems and how HTTP/2 will be the end of many of them.

She showed some of the cool features of HTTP/2 such as more than one request per connection, server push, etc. But she made the focus on another problem: The tools that we currently have doesn't even support HTTP/2 and that is not making the process of the web moving to HTTP/2 faster.

- [Rebecca's HTTP/2 bookmarks](https://pinboard.in/u:rmurphey/t:http2/)

## Lightning talks

From the talks I didn't take any notes as I has trying to understand what they were saying. There were some sound problems.

### Johannes Fiala
#### Swagger 


### Vincent Voyer
#### Publishing ES6 Modules [(Slides)](http://slides.com/vvo/authoring-and-publishing-es6-modules-today-dotjs-2015#/)

This Lightning talk explained different ways to publish node modules written in es6 to the NPM repository by converting modules to ES5 before publishing.

### Etienne Margraff
#### Mobile debugging with VorlonJS [(Slides)](http://fr.slideshare.net/emargraff/dotjs-lightning-talk-vorlonjs)

Interesting talks about using this debugging tool on different devices although I didn't get any clear idea of it. The idea is pretty promising as with the current state of mobile debugging is having a device connected to chrome or safari.


### Maxim Salnikov
#### AngularJS 2 

### Nicolas Grenie
#### JAWS 



## Nicolas Bevacqua [(Slides)](https://speakerdeck.com/bevacqua/practical-es6-for-the-modern-javascript-tinkerer)
### ES6 Overview in 350 Bullet Points [(Blog)](https://ponyfoo.com/articles/es6)

I don't have slides about this one but I got a link to his blog where he actually describe the features of the ES6 Syntax which is basically what he did during the talk.

He went through the new syntax JS ES6 introduced on functions, arrow functions and variables.

The topic was not that exciting and in my opinion much of the features were most of the time saving some characters in coding but decreasing readability. Maybe it is because we are not still used to that syntax and in some time will be easier to read and this way

## André Medeiros [(Slides)](https://speakerdeck.com/staltz/the-whole-future-declared-in-a-var)
### The whole future declared in a var

Surprising talk on a really unknown topic for me. I was much enjoying the talk trying to get where I could get to use the features he was presenting on a real project example. The community have to keep an eye on this topic. Observables and events streams are a really difficult concept to explain but Andre did it in a interactive way.

## Eric Schoffstall
### WebRTC

As I announced before this was for me one of my two favorite talks. It was really impressive the way Eric works and the way he gets things done. I look at my notes and didn't have anything other than his name, the topic and the implementation afterward.

The talk was about the problems he had implementing WebRTC in a real project supporting different devices and different browsers in an area where other people is just going native to avoid having this issues or because the area is still to young to be exploited in a real-world project.

At the end of the project he gave us the link for the WebRTC.works he has been developed supporting every major device.

## Forbes Lindsay
### Jade is not jade anymore and now all of us have to change the implementation of our plugins (Own title)

The first thing he said is that Jade is not Jade anymore and from now on will be called Pug. He used the conference to make the announcement and that is why is so exciting coming to these conferences with such speakers.

I have been using jade for some time now I had also some experience using the parts of the jade template transform mechanism. He explained how the parts are working together along a pipe, transforming text to a tree and the back to HTML. Jade 2 (I meant Pug) will be supporting plugins in this piping system and those are good news for the people who is using this system.

## Henrik Joreteg
### POCKET-SIZED JS [(Slides)](https://slides.joreteg.com/dotjs/)

Henrik presented what do don't see or don't want to see. Mobile is a big player but it's going to be even bigger. We are sometimes using Frameworks that are really powerful even for the easiest task and sometimes we don't think on the mobile user enough.

We are delivering way to big websites and that is bad. We should be just using the parts of the framework that we need and not just everything. And we should never forget mobile users.

Hardware is not so strong on the majority of the devices, there are a lot of Android users using old versions of it with old hardware. There is a way to overcome this problem and that is: Web Workers!

We could use Web Workers to do the heavy calculation and this way leave the UI Thread for just updating and painting this new calculated interface.

We should not forget that we are forcing the user sometimes to install a native application just to make it perfomant, to give a better UX to the user. By just creating smaller webapps with better response times and a better administration of the UI Thread we could move away from the native apps. We could move away the closed gardens of the app stores, and also make the application easier to reach to users by progressive introducing the web app.

Really inspiring talk!

## Tim Caswell
### JS Possibilities not just in the browser

Not really what I was expecting in a web conference but also good to know what could be done out of the browser. We may be all just using javascript only for everything we need.

## Brendan Eich
### Web Evolution, progressive introduction of web apps and introduction of Web Assembler

Well, who could close better this amazing evening that Brendan Eich. The reason we are all here in the first place.

Setting what the web looks like right now, we should not forget that the web is more than google chrome, firefox should be used as much as before or it will be the new opera. Microsoft is changing his mind in a lot of topics allowing a better web and increasing the browser competition.

He also talked about how flipkart moved away from the native application into a webapp by progressively introducing the app. Every one of us have many application on their phones that are not being used anymore, that's because we have to install an application every time we want to get a service. We could just instead add a Bookmark in our home screen and it would be the same if it's done the right way.

He also introduced the possibilities that web Assembler is bringing into the web. And in the middle of the talk, he started playing a zombie videogame to show us what the possibilities out there if we all, as a community, push a better web.


## Conclusion

I don't know how can I express everything I have lived in Paris the last weekend, the locations were great, I have meet some curious and cutting edge libraries (Hyperdrive as an example), I have met also a lot of people who are pushing the limits of the web making the web the best of it. We had lots of fun and the Conference worked like a charm.

Cheers to the organization, It looked like is a really easy task to organize a conference for +1000 people. Food was cheesy and sugary and they will see it on the feedback forms.

Thanks and see you next year.

## Collaboration
Please fell free to send a pull request so we can have a better output from the conference.
