# Future-Self Avatar for Dieting Interventions

This project provides a tested avatar-based feedback system aiming to foster healthy intention-building by raising awareness of the risks and potential outcomes of an unhealthy diet, specifically those of high salt consumption.

The avatar was tested to produce positive health outcomes in the following study.

*Fuchs, K., Meusburger, D., Haldimann, M., Ilic, A., NutritionAvatar: Designing a Future-Self Avatar for Promotion of Balanced, Low-Sodium Diet Intention, CHItaly2019*

## Context

We implemented the avatar using HTML, JavaScript and the vector creation tool Adobe Illustrator.
We integrated the avatar into a pre-existing Swiss FoodTracker app as a WebView. The Swiss FoodTracker app is not included in this project.

As an example, we used the Swiss FoodTracker server to store all food items, user data and logic for calculating users’ intake levels (by Klaus Fuchs and Sven Brunner).
We added database fields to accommodate avatar data and implemented the Python script logic to calculate users’ health stages (e.g. healthy heart = stage 2) and messages based on a respective diet.

## Avatar Framework (JS and Artwork)

The avatar design is illustrated under [Design](https://github.com/DanielMeusburger/FutureSelfAvatar/blob/master/illustrations/summary.png).
A example of the avatar is available at [here](http://www.workplayce.de/avatar/avatar.html).

The uploaded version of the code removed all references to connecting to the server it was used and instead uses hard-coded examples for
a) the avatar health stage data (e.g. scores)
b) the artwork uploaded with the project

To install this upload all the files to a server and embed references to a server which provides health data to the *avatar.js*

**Built With**

The avatar was built with
* [William Malone](http://www.williammalone.com/articles/create-html5-canvas-javascript-game-character/1/) - Framework used as an example to create this Avatar Framework
* [jQuery](https://jquery.com/)

**License**

This [avatar framework](https://github.com/DanielMeusburger/FutureSelfAvatar/tree/master/framework) (JS file and artwork) is licensed under the MIT License - for more information see [License](https://github.com/DanielMeusburger/FutureSelfAvatar/blob/master/LICENSE) and [avatar.js](https://github.com/DanielMeusburger/FutureSelfAvatar/blob/master/framework/avatar.js)

## Avatar Mobile App
TBC

## Avatar Server
TBC

## Implemented by

* **Daniel Meusburger** - *Concept creation, avatar development, server configuration and artwork* - [Link](http://www.workplayce.de/portfolio/about.html)
* **Klaus Fuchs** - *Supervision, app development and concept creation* - [Link](https://im.ethz.ch/people/kfuchs.html)
* **Sven Brunner** - *Technical advise, app development and server configuration* - [Link](https://www.linkedin.com/in/sven-brunner-7ba3bb106/)
