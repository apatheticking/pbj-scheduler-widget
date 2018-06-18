##PBJ Scheduling Widget

An online booking widget that allows you to book an appointment with a small business using google calendar. This widget allows you select a service that a busienss offers and lets you choose the day and time. Once you've picked a day enter your contact information and from there you can choose how to be notified either by text or email and it will send you an google calendar invite. This application also uses the Stripe API to allow users to pay for their services via credit card.

##Contributors
Jeffrey Lee - https://github.com/apatheticking
Peter Goshulak - https://github.com/pgoshulak
Ben Yoo - https://github.com/benyoo5222

##Screenshots
![screenshot from 2018-06-17 21-38-06](https://user-images.githubusercontent.com/3837841/41514656-c9513776-7276-11e8-8011-fa0b1a8f86b4.png)

![screenshot from 2018-06-17 21-38-57](https://user-images.githubusercontent.com/3837841/41514673-e05e9580-7276-11e8-9fa9-74662b3bfefe.png)

![screenshot from 2018-06-17 21-39-41](https://user-images.githubusercontent.com/3837841/41514688-f67b0b96-7276-11e8-95ac-17292e7f63c5.png)

![screenshot from 2018-06-17 21-40-20](https://user-images.githubusercontent.com/3837841/41514709-0fbc2eb4-7277-11e8-83e4-14d7c209466e.png)

##How to run
-first download the server from this link below
https://github.com/apatheticking/pbj-business

-once you've downloaded the server go into the server folder and run the command 'npm run dev-server'.
-back in the pbj-scheduler-widget folder run the command 'npm start'

##Dependencies
"@material-ui/core": "^1.1.0",
"axios": "^0.18.0",
"gh-pages": "^1.2.0",
"moment": "^2.22.1",
"moment-range": "^4.0.1",
"react": "^16.4.0",
"react-big-calendar": "^0.19.1",
"react-dom": "^16.4.0",
"react-scripts": "1.1.4",
"react-stripe-checkout": "^2.6.3",
"react-stripe-elements": "^2.0.0",
"stripe": "^6.1.0"

##What I would improve on next
-Add Validation to each of the text fields
-Look into https in order to use the Stripe API as a commerical product
