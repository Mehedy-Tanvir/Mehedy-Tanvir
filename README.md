<div align="center">

![Profile Banner](/assets/banner.png)

# Hi there 👋

I'm Md. Mehedy Hasan Tanvir, a passionate MERN stack developer from Mymensingh, Bangladesh. Welcome to my GitHub profile! 🚀

## 💻 What I Do

I specialize in building dynamic and scalable web applications using the MERN stack. From crafting responsive user interfaces with React.js to developing robust server-side applications with Node.js and Express.js, I bring ideas to life. My expertise also extends to database management with MongoDB and creating seamless full-stack solutions.

## 📊 GitHub Stats

[![GitHub Streak](https://github-readme-streak-stats.herokuapp.com?user=Mehedy-Tanvir&theme=green-nur)](https://git.io/streak-stats)

## 🔧 Technologies That I Know

[![My Skills](https://skillicons.dev/icons?i=html,css,tailwind,javascript,react,nodejs,expressjs,mongodb,firebase&perline=9)](https://skillicons.dev)

## 👀 Current Overview

### 🔭 I’m working

Currently I am working as a Full Stack Developer at FlowAppz.

### 🌱 I’m exploring

Delving into React Native to enhance my expertise.

### 👯 I’m looking

Seeking opportunities to collaborate on exciting open-source projects.

### 🤔 I’m trying

Dedicated to helping individuals learn and grow in the field of web development.

### ⚡ Fun fact

I can speak Hindi.

## 📫 How to reach me

<div align="center">
  <div style="display: flex; justify-content: center; align-items: center; gap: 30px;">
    <a href="mailto:mehedytanvir451@gmail.com">
      <img src="./assets/gmail.svg" alt="Gmail Logo" width="50" height="50">
    </a>
    <a href="https://www.linkedin.com/in/mehedytanvir">
      <img src="./assets/linkedin.svg" alt="LinkedIn Logo" width="50" height="50">
    </a>
  </div>
</div>

## 🚀 Last Projects

<div align="left">

### 1. **Destinize**

#### Project Features

- This is a 3 role web app as follows Admin, Tour Guide, Tourist.
- Admin can add travel packages and manage users (make admin and tour guide).
- Here authenticated users can book packages, cancel them, if eligible can apply discount and make payment. They can also add packages to their wishlist and remove them.
- Tour guide can accept and reject bookings, update their profiles.
- Authenticated users can also make review in Tour guide profiles.
- Authenticated users can also write stories which are showcased to visitors.
- Mongodb database is used with Mongoose.
- Both email-password and social based authentication is implemented by firebase.
- Stripe Payment system is implemented in this project.
- JWT based authentication is implemented.
- Axios interceptor functionality is implemented.
- There is 404 error page.
- Dynamic loading page is shown on loading.
- Successful or failed crud operations and authentications operations will show meaningful toast.
- In the navbar when users log in he or she can see his image and dashboard.

#### Technology Used

- **Frontend:**

  - React.js
  - React Router
  - Tailwind CSS
  - Daisy UI

- **Backend:**

  - Node.js
  - Express.js
  - MongoDB (Mongoose)

- **Authentication:**

  - Firebase (Email-password and social-based authentication)

- **Payment:**

  - Stripe

- **Other Libraries:**

  - JWT (JSON Web Token)
  - Axios
  - Tanstack Query
  - React Hot Toast
  - React Rating
  - Framer Motion
  - React Awesome Slider
  - React Confetti
  - React Datepicker
  - React Helmet Async
  - React Icons
  - React Share
  - React Simple Captcha
  - Sweet Alert 2

- **Deployment:**

  - Client side was hosted to Firebase
  - Server side was hosted to Vercel

#### Client Repository

- [https://github.com/Mehedy-Tanvir/destinize-travel-guide](https://github.com/Mehedy-Tanvir/destinize-travel-guide)

#### Server Repository Link

- [https://github.com/Mehedy-Tanvir/destinize-travel-guide-server](https://github.com/Mehedy-Tanvir/destinize-travel-guide-server)

#### Live Links

- [https://destinize-tour-guide.web.app/](https://destinize-tour-guide.web.app/)
- [https://destinize-tour-guide.firebaseapp.com/](https://destinize-tour-guide.firebaseapp.com/)

### 2. **Travello Local Tour**

#### Unique Feature

- Editing id's on the URL of the browser may lead to the crashing of the server. To address this, I created a middleware named `verifyId` on the server side, which checks if requests contain a valid id. If the id is not valid, it sends a 404 status code to the client side. This error is tracked by the Axios interceptor, and if such an error occurs, the user is redirected to the home page, showing an invalid id toast.

#### Project Features

- In the home page, it contains Banner, Popular Services, Things You Need To Know, Our Memories, and Subscription sections. All pages contain a navbar and footer. Initially, the home page loads four popular services data from the server, which is stored in MongoDB. Clicking the show all button below the popular services section will redirect the user to the services page.
- In the services page, there is a search by service name implemented. Initially, it shows 6 services and a show more button. Clicking the show more button will display all the services.
- In the service card, there is a show details button. If the user is logged in, the user can show the detail page of the service and go further.
- In the show detail page, there are also other products from the same provider. Clicking them will redirect the user to their detail page.
- In the show detail page, clicking the book button will open a modal where there shows service information, and the user can input the date and instruction and then purchase the service.
- Users can see their bookings and pending works on the my schedule page.
- Users can also add a service by submitting a form on the add service page.
- Users can see their added services on the my added services page.
- From the my services page, users can update and delete their services.
- If anyone books their services, it will show on their my schedule's my pending work section. From here, they can update the status of the service to in progress or completed. Initially, the status is pending.
- Both email-password and social-based authentication are implemented by Firebase. Only the home page and all services pages are public.
- JWT-based authentication is implemented.
- Axios interceptor functionality is implemented.
- There is a 404 error page.
- Dynamic loading page is shown on loading.
- Successful or failed CRUD operations and authentication operations will show meaningful toasts.
- In the navbar, when users log in, they can see their image and name.

#### Technology Used

- **Frontend:**

  - React.js
  - React Router
  - Tailwind CSS
  - Daisy UI

- **Backend:**

  - Node.js
  - Express.js
  - MongoDB

- **Authentication:**

  - Firebase (Email-password and social-based authentication)

- **Other Libraries:**

  - JWT (JSON Web Token)
  - Axios
  - React Hot Toast
  - Tanstack Query
  - Framer Motion
  - Lottie React
  - React Icons
  - Prop Types

- **Deployment:**

  - Client side was hosted to Firebase
  - Server side was hosted to Vercel

#### Client Repository

- [https://github.com/Mehedy-Tanvir/tour-guide-client](https://github.com/Mehedy-Tanvir/tour-guide-client)

#### Server Repository

- [https://github.com/Mehedy-Tanvir/tour-guide-server](https://github.com/Mehedy-Tanvir/tour-guide-server)

#### Live Links

- [https://travello-local-guide.web.app/](https://travello-local-guide.web.app/)
- [https://travello-local-guide.firebaseapp.com/](https://travello-local-guide.firebaseapp.com/)

### 3. **NEXUS BRAND STORE**

#### Project Features

- In the home page, it has 6 sections, which are Navbar, Banner, Brands, FAQ, and Contact NEXUS. The home page initially loads brand data from the server, which is stored in the database and shows them in cards of the brands' section.
- The Navbar contains a theme toggle button, user image (if logged in), user name (if logged in), home, add product, my cart, login/logout (depending on the user logged in or not).
- Users can change the theme between dark and light by clicking the moon and sun buttons located at the Navbar. The user's theme preference is stored in local storage so that reloading and reopening the browser will not change the theme.
- Clicking on the brands' cards will redirect you to the respective brands' products page.
- The brand products' page contains a slider containing 4 ads images and corresponding brand products.
- In the brand products' page, product information with detail button and update button are shown.
- Clicking the detail button will redirect the user to the detail page, where there is an add to cart button. The detail page is a private route that cannot be accessed without login.
- Clicking the add to cart button in the detail page will add products to your cart (will add that product to that user's name in the database).
- Users can see their added-to-cart products in my cart page. Users can also remove products from my cart by clicking the delete button. It is a private route.
- Clicking add product in the navbar, the user is redirected to the add product page, where there is a form to add a product. Submitting the form will add that product to the database, which can be later seen in the brand's products page. Add products is a private route.
- Clicking the update button on the products page for each product will redirect the user to the update page, where the data of that product is preloaded and set as the default value in the update form. After updating and submitting the form, it will update the product's information. This update page is a private route.
- Login and register page can be toggled by clicking login below the register form and register below the login form.
- When registering, it checks if the password is a minimum of 6 characters, containing a capital letter, containing a special character, and gives an error toast when these conditions are not met.
- The Firebase authentication system is implemented in this project.
- After a successful registration, it will show a success toast message; otherwise, show an error toast containing an error message.
- After a successful login, it will show a success toast message; otherwise, show an error toast containing an error message.
- After a successful profile update, it will show a success toast message; otherwise, show an error toast containing an error message.
- Clicking logout will log out the user and show a success toast message.
- There is an error page. If the user tries to access a page that is not available, then the error page will be rendered.

#### Technology Used

- **Frontend:**

  - React.js
  - React Router
  - Tailwind CSS
  - Daisy UI

- **Backend:**

  - Node.js
  - Express.js
  - MongoDB

- **Authentication:**

  - Firebase (Email-password and social-based authentication)

- **Other Libraries:**

  - React Hot Toast
  - Prop Types
  - React Icons
  - React Rating

- **Deployment:**

  - Client side was hosted to Firebase
  - Server side was hosted to Vercel

#### Client Repository

- [https://github.com/Mehedy-Tanvir/brand-shop-client](https://github.com/Mehedy-Tanvir/brand-shop-client)

#### Server Repository

- [https://github.com/Mehedy-Tanvir/brand-shop-server](https://github.com/Mehedy-Tanvir/brand-shop-server)

#### Live Link

- [https://nexus-brand-store.web.app](https://nexus-brand-store.web.app)

</div>
</div>
