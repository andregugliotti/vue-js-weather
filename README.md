# Vue JS Weather App

This is a simple Vue JS application, based over Openweather API. This was built
 as a start point when learning Vue JS as many say that it's cool and a great
 framework for web applications.

The initial work was done by Tyler Potts and can be found on
 [this repository](https://github.com/TylerPottsDev/weather-vue). It's a basic
 Vue JS site which presents a search bar and calls Openweather API endpoint.
 Based on the response, the values are populated on the container and the
 background is changed.

## Development

To work in a local environment, just clone this repository and issues the
 following command:

`npm install`

Then, you can start a dev server typing in:

`npm run serve`

Your web application will be available on `http://localhost:8080`

Oh, you don't know what npm is? Don't worry, Google is your friend, ;)

## Possible next steps

As said, this is just a fun project that can guide somebody (me!) on learning Vue JS.
 But, having time on next weeks, I believe there are some tasks that would be great to
 achieve:

[ ] improve the request, moving it to async and handling errors

[ ] review Openweather request as having cities name on the call is going to be
 deprecated (a geocode API should be used prior to the weather request)

[ ] a better graphic, displaying more information, and maybe improving mobile views

[ ] a suggested cities list, while the name of the city is being typed

[ ] geolocation to determine the city

[ ] PWA-ready

[ ] ability to set a city as favourite and receive weather alerts

[ ] some kind of integration with Netlify or Heroku allowing fast deployments

[ ] some kind of automatic tests

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you
 would like to change. Please make sure to update tests as appropriate.

## Authors

- [Andre Gugliotti](https://github.com/andregugliotti)

## License

GNU/GPL v3
