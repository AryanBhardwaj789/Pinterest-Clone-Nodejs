# Pinterest-Clone-Nodejs

## Description

The Pinterest Clone Project is a web application designed for users to register, log in, and manage their own boards where they can save and organize various pins. Users can create boards, upload pins, and share them with others, providing a seamless experience for discovering and managing content.

## Features

- **User Registration and Login**: Secure user authentication and authorization using Passport.js.
- **Profile Management**: Users can view and manage their profiles, including their boards.
- **Feed Page**: A feed displaying all the different pins available to users.
- **Save Pins**: Users can save pins to their boards.
- **Delete Pins**: Users can remove pins from their boards.
- **Edit Pins**: Option to edit existing pins.
- **Upload Pins**: Users can upload new pins directly to their boards.

## Technologies Used

- **Node.js**
- **Express.js**
- **MongoDB/Mongoose**
- **EJS**
- **Passport.js**
- **Passport-Local**
- **Passport-Local-Mongoose**
- **Multer**
- **dotenv**
- **Cookie-Parser**

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/AryanBhardwaj789/Pinterest-Clone-Nodejs.git
   cd pin
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Create a `.env` file in the root directory with the following content:
   ```
   MONGO_URI=<your-mongo-db-connection-string>
   ```

4. Start the application:
   ```bash
   npm start
   ```

5. Access the application at `http://localhost:3000`.

## Demo

You can check out the live demo of the Pin Project here: [Live Demo](https://pinterest-clone-nodejs.onrender.com/)

## Routes

- `POST /register` - Register a new user
- `POST /login` - Log in a user
- `GET /profile` - View user profile and boards
- `GET /feed` - View the feed of all different pins
- `POST /save/:pinid` - Save a pin to a board
- `DELETE /delete/:pinid` - Delete a pin from a board
- `GET /logout` - Log out a user
- `PUT /edit` - Edit pin details
- `POST /upload` - Upload a new pin

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or features you would like to add.

## Acknowledgments

Thanks to all the contributors and open-source libraries that made this project possible.