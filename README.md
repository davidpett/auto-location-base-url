# Auto-location-base-url

This README outlines the details of collaborating on this Ember application.
A short introduction of this app could easily go here.

* `ember build --environment production` (production)
* edit the `dist/index.html` and remove the `<base href="/" />`
* run `node static_server` and open http://localhost:8080/dist

you should see the error in the console `Uncaught UnrecognizedURLError: /dist/`.

if you run `bower i --save ember#release` and follow the above steps, it works correctly.

you will also get the error if you run on 1.12.0
