## Heroku Selfie Code Challenge

Deploy your selfie app on Heroku for special edition Heroku swag.

Rules:

1. The app must be deployed to Heroku.
2. The app must display a selfie of yourself at the Heroku booth.
3. Tell your app name to someone at the Heroku booth to claim your Heroku swag.

If you are already familiar with Heroku, you can build your selfie app with
any language you want. If you aren't familiar with Heroku, follow along with
the directions below.

### Prerequisites

1. A Heroku account. You can get one for free at [signup.heroku.com](https://signup.heroku.com/).
2. The Heroku toolbelt. You can get it at [toolbelt.heroku.com](https://toolbelt.heroku.com/).
3. A git client. You can use the command line, SourceTree, or Github.

### Command Line Example Procedure

1. Take a selfie of yourself at the Heroku Booth.
2. Clone this repository to your machine with `git clone https://github.com/heroku/selfie.git`.
3. Enter this app's directory with `cd selfie`.
4. Edit index.html with the url to your selfie, and save your
   changes.
5. Commit your changes with `git add -A && git commit -m "Add my selfie"`
6. Create your heroku app with `heroku apps:create`.
7. Push your app to heroku with `git push heroku master`.

Your app is now live at your-app-name.herokuapp.com! Show off your app to
someone at the Heroku booth to snag special Heroku swag.
