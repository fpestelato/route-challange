# route-challange

This project have objective to test the MERN (MongoDB, Express.js, React.js, Node.js) stack skills and also good pratices.
The user could is able to search an address and it geo location provided by <a href="https://developers.google.com/maps/documentation/geocoding/overview?hl=pt-br">Google GeoCode API</a> and register deliveries. Using the <a href=">React-Leaflet</a> to present interactive maps showing the deliveries.

The database collections is currently online at a free cluster in MongoDB Atlas.

At the backend, I used Nest.js framework which provide a lot build-in features speeding up the development.
The beckend have 100% unit test coverage, you can test it using: 

```bash
$ npm run test:coverage
```
The frontend is pretty deafult React coding with hooks. I tried to abstract as much as I can to segregate it in components to be reusable a clean code.
To validate the form data I used <a href="https://react-hook-form.com/">React Hook Form</a>

I didn't use any UI frameworks. I was wondering just to keep it simpl but also elegant respecting the desired layout in the challange. And this is the final look!

<img src="https://i.ibb.co/bHh5cVs/img.png" alt="Project Image"/>

There is a lot of space to improvements, but this is all for now! Hope you all enjoy 😀!
