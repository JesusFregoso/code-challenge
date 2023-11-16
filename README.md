# Simple Developer Exercise 

The savvy cats over at SMART Pump would like to be able to allow users to login to their account, check their balance and update their personal details. Write a simple web application (API and UI) using node.js and lowdb that lets users accomplish those tasks. 

Feel free to use any other libraries or tool chains as long as the core code is javascript and node.js. npm (https://www.npmjs.org) is your friend - no need to recreate the wheel. 

You will find the base data file in `/data`

Wireframes: `assets/wireframes.png`

## Time limits

This exercise is meant showcase your creativity and talent in problem solving against a real world scenario. To that end it should not consume your every waking moment. We recommend at max spending 3 evenings of time on the exercise. 

## Requirements

* Login to the app via email and password (✅)
* Restrict access to valid a User (✅)
* Once logged in show the details of the user on the page (✅)
* Authorized users can check their account balance (✅)
* Authorized users can add fund or withdraw from their account balance (✅ ✅)
* Authorized users can add fund or withdraw from their account balance (✅ ✅)
* Allow the user to change their details (✅)
* lowdb (DB) -> https://github.com/typicode/lowdb (✅)
* node.js -> http://nodejs.org/ (✅)

## Bonus Points

* Fully responsive UI (✅)
* Unit Tests of the API (❌)
* Functional Tests of the UI (❌)


## Features

In the `app` folder, you will find the following features already implemented:

1. User Authentication: Users can log in to the application using their email and password.
2. Access Restriction: Only valid users are allowed to access the application.
3. User Details Display: Once logged in, the application displays the details of the user on the page.
4. Account Balance: Authorized users can check their account balance.
5. Funds Management: Authorized users can add funds or withdraw from their account balance.
6. User Details Update: Users can change their personal details.

## Getting Started

To run the application, follow these steps:

1. Clone the repository to your local machine.
2. Navigate to the `app` folder.
3. Install the necessary dependencies using npm: `npm install`.
4. Start the server: `npm start`.
5. Open your web browser and access the application at `http://localhost:3000`.

## Testing

Unit tests and functional tests are yet to be implemented. You can add tests to ensure the reliability and functionality of the application.

## Contributing

Contributions are welcome! If you have any ideas or improvements, feel free to submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).