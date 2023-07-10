<h1 align="center" style="color:blue"><b>The Myntra Clone</b></h1>

<br>

<p align="center">
<img style="display:block; margin:auto; " src="https://myntradine.netlify.app/images/mainLogo.png" width="230px" alt="Error 404">
</p>

<br>

## Project Name : `MYNTRA`

<br>

# About :

<b>Myntra ia an E-commerce site where user can login or signup and buy diffrent things like myntra.com. User also can sort and filter the products.</b>

<br>

## Deployed Link :

   - Frontend: <a href="https://myntradine.netlify.app/">Netlify</a>
   - Backend: <a href="https://myntra-tun3.onrender.com">Render</a>


<br>

# Requirements : 

- User can login and sign up
    -Used Bcrypt and Jsonwebtoken
- User can visit pages 
- User can see products 
- User can add products to wishlist
    - User can view vishlist 
    - User add products from wishlist to cart
    - User can cancel product
    - User can place order
    - User can pay amount
- Logout 

<br>



<br>

# Tech stack :

### Frontend 

- HTML
- CSS
- JavaScript

### Backend 

- Node.js 
- Express.js

### Database

- MongoDB 


# Schema : 

- User 
      name: { type: String, required: true, maxLength: 15, minLength: 4 },
    email: {
      type: String,
      required: true,
      unique: true,
      validate: validator.isEmail,
    },
    pass: {
      type: String,
      required: true,
      minLength: 4,
    },
    phone: {
      type: String,
      required: true,
      minLength: 10,
    }


- Products 
    image_url: { type: Object, required: true },
    brand: { type: String, required: true },
    subtext: { type: String, required: true },
    price: { type: Number, required: true },
    mrp: { type: Number, required: true },
    offer: { type: Number, required: true },
    category: { type: String, required: true },
    gender: { type: String },
    rating:{type:Number},
    discount:{type:Number}

- cart 
     userID: { type: String, required: true },
  title: { type: String, required: true },
  image: { type: String, required: true },
  price: { type: Number, required: true },
  desc: { type: String, required: true },
  qty: { type: Number, required: true },

<br>


# API EndPoints :

<h3>
    <strong>
      <a href="https://dent-care-backend-aa29.onrender.com/api-docs" target="_blank">Swagger Docs for Api</a>
    </strong>
</h3>

<br>

## Run Locally

Clone the project

```bash
  git clone https://github.com/aniketbabariya24/myntra.git
```

Go to the project directory

```bash
  cd Backend
```

Install dependencies

```bash
  npm install
```

Start the server

```bash
  npm run start
```
------------
<br>

<h2>HomePage</h2>
<img src="https://github.com/aniketbabariya24/tough-health-8180/assets/112626195/e8d835dc-e346-41f9-9e29-e9d448fc39d7" alt="">

<br>

<h2>Sign In / Sign Up page</h2>
<img src="https://github.com/aniketbabariya24/tough-health-8180/assets/112626195/d6d4a31a-0287-413e-b3e5-825c9ba4c477" alt="">

<br>

<h2>Service Page</h2>
<img src="https://github.com/aniketbabariya24/tough-health-8180/assets/112626195/202ad3b2-8f87-4f60-8c06-1b1ede6c5748" alt="">

<br>

<h2>Doctors Page</h2>
<img src="https://github.com/aniketbabariya24/tough-health-8180/assets/112626195/ec4b0cfd-a109-4fd5-b01b-f7f2adff2d7f" alt="">

<br>

<h2>Appoinment Book Page</h2>
<img src="https://github.com/aniketbabariya24/tough-health-8180/assets/112626195/6dcca0dd-bf38-4db5-a7c3-7eeb11097ec4" alt="">

<br>

<h2>Admin Page</h2>
<img src="https://github.com/aniketbabariya24/tough-health-8180/assets/112626195/c7f9683e-e933-467b-b792-02007a1154bb" alt="">

