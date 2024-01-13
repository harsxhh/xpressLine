# XpressLine - Delivery Website
Welcome to XpressLine, a robust delivery website built using React, Node.js, Express, and MongoDB. This project provides users with a seamless experience for ordering medicine, groceries, and parcel deliveries. The application supports user authentication via email and password, hashed for security, or through Google login. Additionally, phone numbers are verified using the Twilio API, ensuring a secure and reliable registration process.

# Features
1. **User Authentication**<br>
Users can register and log in using their email and password.
Passwords are securely hashed and stored in the MongoDB database.<br>

2. **Google Login**<br>
Seamless integration with Google login for a convenient authentication process.<br>
3. **Phone Number Verification**<br>
Twilio API is utilized to send OTPs for phone number verification during the registration process.<br>
4. **Medicine, Grocery, and Parcel Delivery**<br>
Users can place orders for medicine, groceries, and parcel delivery.<br>
5. **Parcel Delivery**<br>
Users can enter pickup details and choose pickup and drop-off locations on a map, integrated using the MAPBOX API.<br>
6. **Cost Calculation**<br>
The cost of delivery is generated using a formula to provide transparency to users.<br>
7. **Payment Gateway**<br>
Stripe Payment API is used to visualize and demonstrate the payment gateway for a secure and smooth transaction process.<br>
8. **Order Details**<br>
All order details are stored in the MongoDB database for easy tracking and management.<br>
9. **Forgot Password**<br>
Users have the option to reset their password through a forgot password link sent via nodemailer.<br>
10. **Grocery and Medicine Order Management**<br>
Users can choose from various items for grocery and medicine deliveries, with the ability to add items multiple times. Redux is employed to manage item counts effectively.<br>

# Setup Instructions
<ul><li><em>Clone the repository to your local machine.</em>
  <br>
git clone https://github.com/your-username/XpressLine.git<br>
</li>
  <br>
<li>
  <em>Install dependencies for the client and server.</em>
<br>
cd XpressLine/client<br>
npm install --legacy-peer-deps<br>
cd ../server<br>
npm install<br>
</li>
  <br>
<li><em>Set up environment variables.</em><br>
Create a .env file in the server directory with the necessary credentials for MongoDB, Twilio, MAPBOX, and Stripe.
Run the application.</li>
<br>
<li>
  <em>Start the server</em><br>
cd ../server<br>
npm start<br>
</li> 
<br>
<li>
  <em>Start the client</em><br>
cd ../client<br>
npm start<br>
  
  **Open your browser and navigate to http://localhost:3000 to access XpressLine.**
</li> 
</ul>

# Technologies Used
<ul><li>React</li>
<li>Node.js</li>
  <li>Express</li>
  <li>MongoDB</li>
  <li>Twilio API</li>
  <li>MAPBOX API</li>
  <li>Stripe Payment API</li>
  <li>Redux</li>
  <li>NodeMailer</li>
</ul>









# Contributions
We welcome contributions from the community to enhance and improve XpressLine. Feel free to submit issues, feature requests, or pull requests.

Thank you for choosing XpressLine for your delivery needs!
