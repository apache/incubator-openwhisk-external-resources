# Awesome OpenWhisk [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [<img src="https://raw.githubusercontent.com/openwhisk/openwhisk/master/docs/images/whisk_icon_full_color_with_tm_100x100-300dpi.png" width="100" align="right" alt="openwhisk">](https://github.com/openwhisk/openwhisk)

> Awesome [OpenWhisk](https://www.github.com/openwhisk/openwhisk) resources and tips.

*OpenWhisk is a cloud-first distributed event-based programming service. It provides a programming model to upload event handlers to a cloud service, and register the handlers to respond to various events.*

*Learn more at [http://openwhisk.org](http://openwhisk.org) or try it on [IBM Bluemix OpenWhisk](https://bluemix.net).*

## Contents

- [Tutorials](#tutorials)
- [Sample Applications](#sample-applications)
- [Articles](#articles)
- [Books](#books)
- [Media](#media)
- [Runtimes](#runtimes)
- [Feed Providers](#feed-providers)
- [Utilities](#utilities)
- [Support](#support)


## Articles

*Articles, tutorials and blogs on building serverless applications using OpenWhisk.*
- [Five minute intro to open source serverless development with OpenWhisk](https://medium.com/openwhisk/five-minute-intro-to-open-source-serverless-development-with-openwhisk-328b0ebfa160).
- [Your business won't use a server in 5 years](https://blogs.adobe.com/conversations/2016/12/your-business-wont-use-a-server-in-5-years.html) - Blog post from Adobe on why they got involved with the Apache OpenWhisk project.
- [Squeezing the milliseconds: How to make serverless platforms blazing fast!](https://medium.com/openwhisk/squeezing-the-milliseconds-how-to-make-serverless-platforms-blazing-fast-aea0e9951bd0) - A follow up to "Uncovering the magic" below, this article takes a closer look at OpenWhisk performance characteristics.
- [Whisking the Weather!](https://medium.com/openwhisk/whisking-the-weather-74ecda4d7105) - How and why a mobile app developer developed a unique and fun weather app called Weather Gods with OpenWhisk.
- [Advanced debugging of OpenWhisk actions](https://medium.com/openwhisk/advanced-debugging-of-openwhisk-actions-518414636932) describes how to test an Apache OpenWhisk action locally using Docker and a helper Python script.
- [Extending OpenWhisk to the IoT Edge with Node-RED, Docker and resin.io](https://medium.com/openwhisk/extending-openwhisk-to-the-iot-edge-with-node-red-docker-and-resin-io-bec7f30ea2de) - Describes a sample application for a flexible edge platform using OpenWhisk, Node-RED and resin.io to manage provisioning and lifecycle of Docker-based applications on a fleet of IoT gateways, such as Raspberry Pi.
- [OpenWhisk and The Serverless Framework](https://medium.com/openwhisk/openwhisk-and-the-serverless-framework-b05ce569137a#.n1lyyw17v) - Build serverless apps with OpenWhisk and The Serverless Framework.
- [Uncovering the magic: How serverless platforms really work!](https://medium.com/openwhisk/uncovering-the-magic-how-serverless-platforms-really-work-3cb127b05f71) - A step by step guide through the inner guts of OpenWhisk.
- [HTTP handlers with OpenWhisk](https://medium.com/openwhisk/serverless-http-handlers-with-openwhisk-90a986cc7cdd) - This blog post demonstrates the use of OpenWhisk web actions to write HTTP handlers.
- [What makes serverless architectures so attractive?](https://developer.ibm.com/opentech/2016/09/06/what-makes-serverless-attractive/) - Serverless is the hottest trend in cloud this year, and for good reason.
- [OpenWhisk Planner Bot](https://developer.ibm.com/open/2016/05/13/openwhisk-planner-bot/) - Plan your conference schedule with a serverless recommendation bot
- [Building a Phrase Translator](http://www.ibm.com/developerworks/cloud/library/cl-openwhisk-node-bluemix-user-facing-app/index.html) - Implementing a user interface with serverless functions.
- [Subscribe to RSS Feeds via OpenWhisk](http://blog.ibmjstart.net/2016/08/31/subscribe-rss-feeds-using-new-openwhisk-package/) - Use Trigger Feeds to connect Actions to RSS Feed events.
- [Exploring OpenWhisk's REST API](https://amanoblog.wordpress.com/2016/03/03/ibm-bluemix-openwhisk-rest-api/) - Details on the platform API for OpenWhisk.
- [Building an MQTT Feed Provider](http://jamesthom.as/blog/2016/06/15/openwhisk-and-mqtt/) - Walking through add a new Feed Provider for IoT integration.
- [Serverless APIs with OpenWhisk and API Connect](http://jamesthom.as/blog/2016/04/26/serverless-apis-with-openwhisk-and-api-connect/) - Creating public APIs for serverless web applications.
- [Monitoring Apps using OpenWhisk](https://iainhouston.com/blog/openwhisk-workflow.html) - Using Openwhisk to run a Python monitoring app.
- [Combining Twilio with Serverless Functions](https://medium.com/@osipov/polyglot-serverless-computing-using-docker-and-openwhisk-c6ff14e7ed8#.8yqcku48y) - Using Twilio APIs from OpenWhisk Actions.
- [Jess: Serverless & GUI-less App](http://www.markwatsonatx.com/tutorial/openwhisk/serverless/2016/08/04/serverless-guiless-openwhisk.html) - Budgeting application using Twilio and OpenWhisk.
- [Matos: An example of a serverless data pipeline](https://developer.ibm.com/openwhisk/2016/10/04/lightweight-data-pipelines-with-openwhisk/) - building a bridge between Kafka (IBM Message Hub) and OpenStack Swift API (IBM Cloud Object Storage) with OpenWhisk.
- [NPM Modules in OpenWhisk](http://jamesthom.as/blog/2016/11/28/npm-modules-in-openwhisk/) - Using NPM modules in OpenWhisk Actions.
- [Updates to OpenWhisk Node.js actions](https://medium.com/openwhisk/updates-to-openwhisk-node-js-actions-ed5556cd5ae9) - Recent changes including deprecation for the GA release.
- [Another OpenWhisk Cron Example - the Blog Nag](https://www.raymondcamden.com/2017/02/21/another-openwhisk-cron-example-the-blog-nag) - Another demo involving Cron.
- [Building a Form Handler Service in OpenWhisk](https://www.raymondcamden.com/2017/01/25/building-a-form-handler-service-in-openwhisk) and [Building a Form Handler Service in OpenWhisk - Part Two](https://www.raymondcamden.com/2017/02/15/building-a-form-handler-service-in-openwhisk-part-two) - two articles demonstrating using OpenWhisk to handle form submissions.
- [Collecting 911 Data with OpenWhisk Cron Triggers](https://www.raymondcamden.com/2017/02/14/collecting-911-data-openwhisk-cron-triggers) - An example of a Cron-based service.
- [Serverless and Persistence](https://www.raymondcamden.com/2017/02/09/serverless-and-persistence) - Some thoughts on persistence in a serverless environment.
- [Working with OpenWhisk Triggers](https://www.raymondcamden.com/2017/02/02/working-with-openwhisk-triggers) - A look at trigger/rule support in OpenWhisk.
- [Using Packages in OpenWhisk](https://www.raymondcamden.com/2017/01/31/using-packages-in-openwhisk) - A look at package support in OpenWhisk.
- [Talking to your Bot in OpenWhisk](https://www.raymondcamden.com/2017/01/26/talking-to-your-bot-on-openwhisk) - A simple bot demo for OpenWhisk.
- [All My Friends are Superheroes](https://www.raymondcamden.com/2017/01/18/all-my-friends-are-superheroes) - A demo of using the Marvel API with OpenWhisk.
- [Creating Zipped Actions in OpenWhisk](https://www.raymondcamden.com/2017/01/10/creating-packaged-actions-in-openwhisk) - How to use zipped actions with OpenWhisk.
- [Quick Tip for Testing OpenWhisk Actions Locally](https://www.raymondcamden.com/2017/01/09/quick-tip-for-testing-openwhisk-actions-locally) - A simple script/method to test OpenWhisk actions locally.
- [An Example of an OpenWhisk Sequence](https://www.raymondcamden.com/2017/01/06/an-example-of-an-openwhisk-sequence) - A quick tutorial on using sequences with OpenWhisk.
- [Building a Serverless API Proxy with OpenWhisk](https://www.raymondcamden.com/2017/01/02/building-a-serverless-api-proxy-with-openwhisk) - A look at how to build an API proxy with OpenWhisk.
- [Lastversion.info](http://alexanderfortin.tumblr.com/post/157820499911/lastversion-a-go-serverless-proof-of-concept) - An HTTP service to fetch latest stable version of OpenSource projects, written in Go and running as OpenWhisk action. See the releated blog post on [how to use Docker to create a Go-based OpenWhisk action](http://jamesthom.as/blog/2017/01/16/openwhisk-docker-actions/)


## Tutorials

*Tutorials and other material to help you learn OpenWhisk*

- [Official OpenWhisk Tutorial](https://github.com/openwhisk/openwhisk-tutorial) - Interactive tutorial for learning how to use OpenWhisk.
- [OpenWhisk-workshop](https://www.npmjs.com/package/openwhisk-workshop) - This workshop will help you learn OpenWhisk and introduce you to the concepts behind the platform using NodeSchool toolchain.
- [60secs Quickstart](http://jamesthom.as/blog/2018/01/19/starting-openwhisk-in-sixty-seconds/) - Starting OpenWhisk in Sixty Seconds


## Sample Applications

*Sample open-source projects built using the OpenWhisk platform*

- [Your first Action, Trigger, and Rule](https://github.com/IBM/openwhisk-action-trigger-rule) - Simple Hello World style demo showing OpenWhisk actions, triggers, and rules.
- [Message Hub and Kafka Data Processing](https://github.com/IBM/openwhisk-data-processing-message-hub) - Create a serverless, event-driven application with OpenWhisk that executes code in response to messages or to handle streams of data records from Apache Kafka or IBM Message Hub.
- [OpenWhisk and Serverless APIs](https://github.com/IBM/openwhisk-serverless-apis) - Create a serverless, event-driven application with OpenWhisk that executes code in response to HTTP REST API calls.
- [Cloudant Data Processing](https://github.com/IBM/openwhisk-data-processing-cloudant) - Create a serverless, event-driven application with OpenWhisk that executes code in response to database changes from Apache CouchDB or IBM Cloudant.
- [Transit IoT](https://medium.com/openwhisk/transit-flexible-pipeline-for-iot-data-with-bluemix-and-openwhisk-4824cf20f1e0) - Comprehensive example of using OpenWhisk for IoT data processing that uses Docker, Node-RED, Message Hub (Kafka based), Object Storage, Spark and Bluemix Data Science Experience services for data analytics.
- [Emoting](https://github.com/l2fprod/openwhisk-emoting) - Sample “user feedback” app that uses OpenWhisk actions via REST API with pages hosted on GitHub and database in Cloudant.
- [Logistics Wizard](https://github.com/IBM-Bluemix/logistics-wizard) - Enterprise-grade sample application which leverages OpenWhisk and CloudFoundry to build 12-factor style applications. It is a smart supply chain management solution that aims to simulate an environment running an ERP system. Also see [related blog post](https://www.ibm.com/blogs/bluemix/2017/02/microservices-multi-compute-approach-using-cloud-foundry-openwhisk/).
- [Web Actions](https://github.com/openwhisk/openwhisk) - This sample shows how to use OpenWhisk to build a complete Web App. See [related blog post](https://medium.com/openwhisk/web-actions-serverless-web-apps-with-openwhisk-f21db459f9ba).
- [Dark vision](https://github.com/IBM-Bluemix/openwhisk-darkvisionapp) - Application that shows how to use OpenWhisk, Cloudant, Watson Visual Recognition, Object Storage to process video frames, tag and recognize scenes.
- [openwhisk-monitoring](https://github.com/KimStebel/openwhisk-monitoring) - Example of using OpenWhisk to monitor HTTP server status.
- [openwhisk-publisher](https://github.com/IBM-Bluemix/openwhisk-publisher) - Hosting static sites with Jekyll, Object Storage and OpenWhisk.
- [skylink](https://github.com/IBM-Bluemix/skylink) - Connect and control a DJI drone aircraft over the Internet with OpenWhisk.
- [BluePic](https://github.com/IBM-Swift/BluePic) - Photo sharing application for iOS using Swift Actions for the backend.
- [Conference Plan Bot](https://github.com/krook/owplan) - Conference planning bot built using serverless functions.
- [Project OpenFridge](https://github.com/krook/openfridge) - Improving customer service with IoT and event-driven computing.
- [Project OpenChecks](https://github.com/krook/openchecks) - Processes the deposit of checks to a bank account with object storage and OCR.
- [openwhisk-nlc-action](https://github.com/pkhanal/openwhisk-nlc-action) - Docker Action with IBM Watson Natural Language Classifier to classify input text.
- [openwhisk-slackapp](https://github.com/IBM-Bluemix/openwhisk-slackapp) - Serverless Slack app built with Slack Events API and IBM Bluemix OpenWhisk.
- [openwhisk-visionapp](https://github.com/IBM-Bluemix/openwhisk-visionapp) - Image tagging and face detection iOS app built with IBM Bluemix OpenWhisk.
- [openwhisk-jq](https://github.com/ibmets/openwhisk-jq) - OpenWhisk Action wrapping the JQ command-line utility for JSON filtering.
- [Personality Analysis](https://github.com/iwinoto/openwhisk-demo-personalityanalysis) - Analysing political speeches using IBM Watson.
- [Mobile Services Demo](https://github.com/gconan/BluemixMobileServicesDemoApp)- Swift app that for analysing tone and posting to a slack channel.
- [Drink Chooser](https://github.com/SwiftOnTheServer/DrinkChooser)- Example Swift app storing to & reading from Redis recommending a drink to consume.
- [Lastversion](https://github.com/shaftoe/lastversion)- An HTTP service to fetch latest stable version of OpenSource projects, written in Go and running as OpenWhisk action
- [Form processing with OpenWhisk](https://github.com/IBM-Bluemix/OpenWhiskContact) - Process contact form without a backend using IBM Bluemix OpenWhisk and SendGrid. [See live link here](https://ibm-bluemix.github.io/OpenWhiskContact/)

## Books

- [Developing Serverless Applications, A Practical Introduction with Apache OpenWhisk]
(https://www.oreilly.com/programming/free/developing-serverless-applications.csp) - free ebook

## Media

*Podcasts, videos, presentations and other content about OpenWhisk.*

### Videos

- [OpenWhisk YouTube Channel](https://www.youtube.com/channel/UCbzgShnQk8F43NKsvEYA1SA) - Screencast demos, recorded presentations and other videos.
- [Creating OpenWhisk Actions](https://www.youtube.com/watch?v=HEw44Eg-l88) - Running Actions with OpenWhisk
- [Automating Actions](https://www.youtube.com/watch?v=4jRigiMpZF4) - Using Triggers with Actions.
- [OpenWhisk Editor](https://www.youtube.com/watch?v=mdq3BJAGheU&list=PLxVTI8yc_iX7QXYOpBf7B6N3-cwule1yl&index=1) - Exploring the OpenWhisk visual editor.
- [OpenWhisk APIs with API Connect](https://www.youtube.com/watch?v=WP6D47KxSrs&index=2&list=PLxVTI8yc_iX7QXYOpBf7B6N3-cwule1yl) - Building APIs using API Connect.
- [Building Slack Bots with OpenWhisk](https://www.youtube.com/playlist?list=PL0UyhC0D6KABYPvGroXcIeE-4x_yEbdB4) - Using OpenWhisk to build a Weather Slack Bot.
- [Project OpenFridge](https://www.youtube.com/watch?v=0Sl4rWZYo8w) - Improving customer service with IoT and event-driven computing.
- [Build a cloud native app with Apache OpenWhisk](https://developer.ibm.com/tv/build-a-cloud-native-app-with-apache-openwhisk/) - An overview of serverless architectures, introduction to the OpenWhisk programming model, and deployment of an OpenWhisk application on IBM Bluemix.
- [Using Serverless Framework & OpenWhisk](https://www.youtube.com/watch?v=GJY10W98Itc&t=3s) - Using the framework to build OpenWhisk applications.
- RedHat Summit 2018 [breakout session on OpenWhisk](https://www.youtube.com/watch?v=C2u6wVRI-N0)

### Presentations

- [Serverless architectures built on an open source platform](https://www.oreilly.com/ideas/serverless-architectures-on-an-open-source-platform) - Five minute IBM keynote introducing OpenWhisk at the O'Reilly Software Architecture Conference in NYC 2017.
- [Event-driven and Serverless Computing with OpenWhisk](https://www.youtube.com/watch?v=rVGFll1sRY4) - Video from Serverless Conf London 2016 by Andreas Nauerz & Michael Behrendt.
- [OpenWhisk Under the Hood](https://www.youtube.com/watch?v=S-fY1exdbao) - Video from Serverless Conf London 2016 by Stephen Fink.
- [Lightning talk introducing serverless architectures and OpenWhisk](http://www.slideshare.net/DanielKrook/cloud-native-architectures-with-an-open-source-event-driven-serverless-platform) - IBM keynote at CloudNativeCon + KubeCon 2016. [Video](https://www.youtube.com/watch?v=C3PPmlUkarY) also available.
- [Tech Talk about OpenWhisk](https://developer.ibm.com/open/events/dw-open-tech-talk-openwhisk/) - Detailed look at this new open source platform from Stephen Fink.
- [The Future Of Cloud Programming](https://www.youtube.com/watch?v=sV7W-eK2x5U) - IBM Bluemix OpenWhisk Talk @ Codemotion 2016, Amsterdam.
- [Serverless Applications with Cloud Foundry and OpenWhisk](https://www.youtube.com/watch?v=kydt6JgW6_8) - Video from Cloud Foundry Summit 2016.
- [Microservices Without Servers](http://jamesthom.as/blog/2016/09/08/microservices-without-servers/) - Slides, demo videos and sample code from conference talk on building serverless applications with OpenWhisk.
- [Voxxed Days Presentation](https://youtu.be/SpmSu6-BOrI?t=8h9m22s) - Video recording for the Microservices Without Servers talk.
- [OpenWhisk - A platform for cloud native, serverless, event driven apps](http://www.slideshare.net/DanielKrook/openwhisk-a-platform-for-cloud-native-serverless-event-driven-apps) - Presentation from Cloud Native Day Toronto. [Video](https://www.youtube.com/watch?v=sYRiTZ47Cao) also available.
- [The Serverless Paradigm, OpenWhisk and FIWARE](http://www.slideshare.net/AlexGlikson/the-serverless-paradigm-openwhisk-and-fiware) - Presentation at the [FIWARE Summit](https://www.fiware.org/summit/) by Alex Glikson (video [here](https://www.youtube.com/watch?v=_JT63orNAsE)).
- [Official OpenWhisk Slides](http://www.slideshare.net/OpenWhisk) - Presentation decks from OpenWhisk team.
- [Multi-provider Serverless Apps](https://speakerdeck.com/jthomas/taming-serverless-dragons-multi-provider-serverless-apps) - Presentation at [Serverless LDN](https://serverless.london/). [Video](https://www.twitch.tv/videos/119142073).

### Podcasts

- [What Makes IBM OpenWhisk Different? Openness](http://thenewstack.io/exploring-pros-cons-serverless-computing-ibm-openwhisk/) - The New Stack podcast with Andreas Nauerz and Michael Behrendt.
- [The Cloudcast #252](http://www.thecloudcast.net/2016/05/the-cloudcast-252-understanding-ibm.html) - Interview with OpenWhisk team about the future of serverless computing.
- [InfoQ Interview](https://www.infoq.com/news/2016/04/bluemix-ibm-interconnect) - Q&A with Michael Behrendt on IBM's Event-driven Programming Service.
- [#vSurround: Are Serverless Architectures Ready for Primetime?](https://www.youtube.com/watch?v=_Q9Q4L3IdIY) - Roundtable discussion with Daniel Krook (IBM), Adam Johnson (IOpipe), David Wells (Serverless), and Ryan Scott Brown (Red Hat) about serverless definitions, use cases, and what's to come in 2017.



## Runtimes

*Links to samples, libraries and projects for running Actions using different languages*.

### Platform Runtimes

- [JavaScript](https://github.com/openwhisk/openwhisk/blob/master/docs/actions.md#creating-and-invoking-javascript-actions) - OpenWhisk runtime for Node.js (v6).
- [Java](https://github.com/openwhisk/openwhisk/blob/master/docs/actions.md#creating-java-actions) - OpenWhisk runtime for Java 8.
- [Python](https://github.com/openwhisk/openwhisk/blob/master/docs/actions.md#creating-python-actions) - OpenWhisk runtime for Python 2.7
- [Swift](https://github.com/openwhisk/openwhisk/blob/master/docs/actions.md#creating-swift-actions) - OpenWhisk runtime for Swift.
- [Docker](https://github.com/openwhisk/openwhisk/blob/master/docs/actions.md#creating-docker-actions) - OpenWhisk runtime for Docker Actions using SDK.

### Community Examples

- [Scala](https://developer.ibm.com/opentech/2017/01/25/serverless-chat-application-using-openwhisk-docker-scala-ibm-cloudant/) - Example article with Github code for running OpenWhisk Actions in Scala.
- [Haskell](https://github.com/rainbyte/openwhisk-wrapper) - Haskell-based OpenWhisk services
- [Docker Examples](https://github.com/gekola/openwhisk_docker_samples) - Run Clojure, Erlang, Ruby and Rust Actions on OpenWhisk using Docker.
- [Go](http://jamesthom.as/blog/2017/01/17/openwhisk-and-go/) - Blog post and library for building Go language Actions.
- [Rust](http://jamesthom.as/blog/2017/01/18/openwhisk-and-rust/) - Blog post and library for building Rust language Actions.
- [Docker Actions](http://jamesthom.as/blog/2017/01/16/openwhisk-docker-actions/) - Explanation of updated Docker Action runtime.


## Feed Providers

*Examples of integrating OpenWhisk with external event sources.*

- [openwhisk-package-imap](https://github.com/tareqmamari/openwhisk-package-imap) - OpenWhisk Package to expose IMAP emails as a trigger feed.
- [openwhisk-package-template](https://github.com/openwhisk/openwhisk-package-template) - This is a template to be use when creating new packages for OpenWhisk.
- [openwhisk-package-iot](https://github.com/tareqmamari/openwhisk-package-iot) - Package including all actions and feeds of Watson IoT Platform.
- [openwhisk-mqtt-feed](https://github.com/jthomas/openwhisk_mqtt_feed) - MQTT package for OpenWhisk, provides a topic subscriber feed.
- [openwhisk-package-mqtt-watson](https://github.com/krook/openwhisk-package-mqtt-watson) - OpenWhisk MQTT Package for Watson IoT service.



## Utilities

*Tools and utilities to help you be more productive with OpenWhisk*

- [swagger-openwhisk](https://github.com/jeroiraz/swagger-openwhisk) - Generate a fully functional whisk package and actions from a swagger specification
- [openwhisk-webpack](https://github.com/IBM-Bluemix/openwhisk-webpack) - Demonstration of using Webpack to bundle OpenWhisk Actions.
- [openwhisk-es6-action](https://github.com/ddragosd/openwhisk-es6-action) - Sample project showing how to bundle ECMAScript6 actions including unit tests and code coverage.
- [hubot-ibmcloud-openwhisk](https://github.com/ibm-cloud-solutions/hubot-ibmcloud-openwhisk) - Hubot scripts for OpenWhisk.
- [node-red-node-openwhisk](https://www.npmjs.com/package/node-red-node-openwhisk) - Node-RED nodes for interacting with OpenWhisk platform.
- [openwhisk-vscode](https://github.com/openwhisk/openwhisk-vscode) - Plugin for Visual Studio Code to provide OpenWhisk commands.
- [openwhisk-apiapp](https://github.com/l2fprod/openwhisk-apiapp) - Proxies calls to OpenWhisk Actions using NGINX to enables CORS
- [openwhisk-canirequire](https://github.com/l2fprod/openwhisk-canirequire) - Find out which NPM modules can be used in OpenWhisk.
- [whiskify](https://github.com/jthomas/whiskify) - Utility class to help running JavaScript functions as OpenWhisk Actions.
- [Jupyter Notebooks integration](https://gist.github.com/parente/bd0b71f15ba0b97139e5) - Jupyter Notebooks as OpenWhisk Actions
- [logstash-input-openwhisk](https://github.com/jthomas/logstash-input-openwhisk) - Logstash plugin to drain OpenWhisk logs to Elastic Search.
- [wab (whisk activation browser)](https://github.com/psuter/wab) - A terminal-mode browser for inspecting OpenWhisk activations.

### Client Libraries

- [Node.js](https://github.com/openwhisk/openwhisk-client-js) - JavaScript client library for the OpenWhisk platform.
- [Swift](https://github.com/openwhisk/openwhisk-client-swift) - Swift client SDK for OpenWhisk with support for iOS, WatchOS2, and Darwin CLI apps.
- [Python](https://github.com/openwhisk/openwhisk-client-python) - Python client library for the OpenWhisk platform.

## Support

*Got stuck with OpenWhisk? Find help here…*

- [GitHub Issues for OpenWhisk](https://github.com/openwhisk/openwhisk/issues).
- [Stack Overflow #openwhisk](http://stackoverflow.com/questions/tagged/openwhisk).
- [Slack Group #openwhisk](http://slack.openwhisk.org/).
- Twitter [@openwhisk](https://twitter.com/openwhisk)
