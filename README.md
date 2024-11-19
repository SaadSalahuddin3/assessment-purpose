<h1>Demo E-Commerce Website</h1>
<h2>Description</h2>
The Demo E-Commerce Website is a simple and responsive web application designed to simulate an online store. It includes essential e-commerce features like product listings, shopping carts, user authentication, and an admin dashboard for managing products.

<h2>Key Features:</h2>

Product Listings: Users can browse a catalog of products with details like price, description, and images.
Shopping Cart: Users can add products to their cart and manage quantities.

User Authentication: A basic sign-up and login system to store user data and orders.

Admin Dashboard: Admins can manage products and track orders.

Responsive Design: The website is optimized for mobile, tablet, and desktop devices.

Technologies Used

Frontend:
React.js
Bootstrap (for responsive design)
HTML5, CSS3, JavaScript

Backend:
Node.js with Express.js
MongoDB (database for products, orders, and user data)
JWT (JSON Web Tokens for user authentication)

Other:
Git (version control)
GitHub (repository hosting)

Setup Instructions
Prerequisites

Node.js: Ensure that Node.js is installed on your machine. Download it from nodejs.org.
MongoDB: You can either set up MongoDB locally or use a cloud-based database like MongoDB Atlas.
Git: Git must be installed on your system for cloning the repository.
1. Clone the Repository
Start by cloning the project repository to your local machine:

git clone https://github.com/yourusername/demo-ecommerce-website.git
cd demo-ecommerce-website

2. Install Dependencies
Navigate to both the client and server directories and install the required dependencies.

For Backend (Server):

cd server
npm install
For Frontend (Client):

cd client
npm install

3. Set Up Environment Variables
In the server directory, create a .env file and add the necessary configuration variables:

makefile

MONGO_URI=mongodb://localhost:27017/demo-ecommerce
JWT_SECRET=your_secret_key
PORT=5000
If you're using MongoDB Atlas, replace the MONGO_URI with your cloud connection string.

4. Run the Server
To start the backend server, run:

cd server
npm start
The server should be running at http://localhost:5000.

5. Run the Frontend
To start the frontend application, run:

cd client
npm start
The frontend should now be running at http://localhost:3000.

<h2>Usage Examples:</h2>
1. Browsing Products
Visit http://localhost:3000 in your browser.
The homepage displays a list of available products with details like name, price, and a short description.
2. Adding Products to Cart
Click the "Add to Cart" button for any product.
Your cart will be updated with the added product, and you can view your cart by clicking the cart icon in the top-right corner.
3. User Authentication
Users can sign up or log in via the Login/Sign Up button in the navigation bar.
Once logged in, the user's shopping cart will be saved, and they can view past orders.
4. Admin Dashboard
Admin users can access the Admin Dashboard to manage products. The dashboard can be accessed via the Admin link in the navigation bar (only visible to admins).
Admins can add, update, or delete products, as well as view orders placed by customers.
5. Mock Checkout Process
To simulate the checkout process, go to your cart and click Checkout.
Since this is a demo, no real payment is processed. A confirmation message will appear after you complete the mock checkout.