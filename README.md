## Hotel Booking App
It is a booking web application. User can browse, search for hotel with their specific requirements and browse rooms of individual hotel. And check if the room is available for booking and then book. User can sign up with fake mail (There is not any confirmation system during sign up)


## Backend Configuration

1. **Environment Files**: Navigate to the `backend` folder and create two files: `.env`. Add the following contents to the files:

    ```plaintext
    MONGODB_CONNECTION_STRING=

    JWT_SECRET_KEY=
    FRONTEND_URL=

    # Cloudinary Variables
    CLOUDINARY_CLOUD_NAME=
    CLOUDINARY_API_KEY=
    CLOUDINARY_API_SECRET=

    # Razorpay
    RAZORPAY_KEY_ID=
    ```

2. **MongoDB Setup**: 
    - Sign up for an account at [MongoDB Atlas](https://www.mongodb.com/cloud/atlas).
    - Create a new cluster and follow the instructions to set up a new database.
    - Once set up, obtain your MongoDB connection string and add it to the `MONGODB_CONNECTION_STRING` variable in your `.env` files.

3. **Cloudinary Setup**:
    - Create an account at [Cloudinary](https://cloudinary.com/).
    - Navigate to your dashboard to find your cloud name, API key, and API secret.
    - Add these details to the respective `CLOUDINARY_*` variables in your `.env` files.

4. **Razorpay Setup**:
    - Sign up for a account at [Razorpay](https://razorpay.com/).
    - Find your API keys in the dashboard.
    - Add your API key to the `RAZORPAY_KEY_ID` variable in your `.env` files.
    - You need to install https://ngrok.com/ to view payment method in browser.
  
5. **JWT_SECRET_KEY**:
    - This just needs to be any long, random string. You can google "secret key generator".

7. **Frontend URL**:
    - The `FRONTEND_URL` should point to the URL where your frontend application is running (typically `http://localhost:5173` if you're running it locally).

## Running the Application

1. **Backend**:
    - Navigate to the `backend` directory.
    - Install dependencies: `npm install`.
    - Start the server: `npm start`.
  
## Deployment

- Render.com is used for deployment    
 <p align="1eft">Render Demo : https://hotel-booking-no52.onrender.com</p>  

## Tools used

<div align="left">
  <img src="https://cdn.simpleicons.org/visualstudiocode/007ACC" height="40" alt="vscode logo"  />
  <img width="12" />
  <img src="https://cdn.simpleicons.org/mongodb/47A248" height="40" alt="vscode logo"  />
  <img width="12" />
  <img src="https://cdn.simpleicons.org/postman/FF6C37" height="40" alt="postman logo"  />
  <img width="12" />
  <img src="https://cdn.simpleicons.org/windowsterminal/4D4D4D" height="40" alt="Terminal logo"  />
  <img width="12" />
  <img src="https://cdn.simpleicons.org/render/46E3B7" height="40" alt="Render logo"  />
  <img width="12" />
