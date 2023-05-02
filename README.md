# ShopCart
 A Full Stack Ecomerce App with User panel, Admin panel and payement gateway

## Features
- Email & Password Authentication
- Persisting Auth State
- Searching Products
- Filtering Products (Based on Category)
- Product Details
- Rating
- Getting Deal of the Day
- Cart
- Checking out with Google/Apple Pay
- Viewing My Orders
- Viewing Order Details & Status
- Sign Out
- Admin Panel
    - Viewing All Products
    - Adding Products
    - Deleting Products
    - Viewing Orders
    - Changing Order Status
    - Viewing Total Earnings
    - Viewing Category Based Earnings (on Graph)




# ScreenShots
<p float="left">
<img src="https://user-images.githubusercontent.com/115138974/228755029-b37d646d-f571-4360-a936-ba20cc7ca5b9.jpg" height ="400" width ="200">
<img src="https://user-images.githubusercontent.com/115138974/228755050-103934c9-eb5e-479c-89d6-4940171bb248.jpg" height ="400" width ="200">
<img src="https://user-images.githubusercontent.com/115138974/228757329-262cb3fc-48aa-41b7-a03b-820949f9ace9.jpg" height ="400" width ="200">
 <img src="https://user-images.githubusercontent.com/115138974/228757649-ec52e812-97fb-407b-97b0-7e2b6ff9e06f.jpg" height ="400" width ="200">
 <img src="https://user-images.githubusercontent.com/115138974/228757668-26211d7e-585a-415e-a0f0-a3c593afe2f6.jpg" height ="400" width ="200">
 
 <img src="https://user-images.githubusercontent.com/115138974/228758089-b643eee7-4183-4baa-aef2-badaee9539bc.jpg" height ="400" width ="200">
 <img src="https://user-images.githubusercontent.com/115138974/228758105-b9acc3cb-2487-4d81-a3c4-6a3e558236d7.jpg" height ="400" width ="200">
 <img src="https://user-images.githubusercontent.com/115138974/228758142-47a0dd8e-2947-43c8-a868-93963637b8e2.jpg" height ="400" width ="200">
 <img src="https://user-images.githubusercontent.com/115138974/228758177-27164d10-28d5-440b-8483-c20bd30ee370.jpg" height ="400" width ="200">
 
 
 
 <img src="https://user-images.githubusercontent.com/115138974/228758715-73a84bad-aceb-4273-acf8-f588bd0e5231.jpg" height ="400" width ="200">
 <img src="https://user-images.githubusercontent.com/115138974/228758727-30bf6966-0eeb-4187-8dc5-7d7b4f5a0d98.jpg" height ="400" width ="200">
 <img src="https://user-images.githubusercontent.com/115138974/228758753-a616ff27-b344-4459-b7d3-5a39a2c2fe77.jpg" height ="400" width ="200">
 <img src="https://user-images.githubusercontent.com/115138974/228758814-286127fc-99c4-42cd-9f95-0fbea1ea4cf6.jpg" height ="400" width ="200">
  <img src="https://user-images.githubusercontent.com/115138974/228758848-7a69562c-8758-4287-98bd-ab02823e0d08.jpg" height ="400" width ="200">
 
 
 
 </p>


# Demo








**User Pannel**


















https://user-images.githubusercontent.com/115138974/228749020-c7f47736-0370-4025-8af6-86e4ac190bdf.mp4











**Admin Panel**



**Deployed Server Link** -https://shopp-cartt.onrender.com


**Server Code** -https://github.com/Kaps61929/shop_cart_server


## Running Locally
After cloning this repository, migrate to ```Shopp_Cart``` folder. Then, follow the following steps:
- Create MongoDB Project & Cluster
- Click on Connect, follow the process where you will get the uri.- Replace the MongoDB uri with yours in ```server/index.js```.
- Head to ```lib/constants/global_variables.dart``` file, replace <yourip> with your IP Address. 
- Create Cloudinary Project, enable unsigned operation in settings.
- Head to ```lib/features/admin/services/admin_services.dart```, replace ```denfgaxvg``` and ```uszbstnu``` with your Cloud Name and Upload Preset respectively.

Then run the following commands to run your app:

### Server Side
```bash
  cd server
  npm install
  npm run dev (for continuous development)
  OR
  npm start (to run script 1 time)
```

### Client Side
```bash
  flutter pub get
  open -a simulator (to get iOS Simulator)
  flutter run
```

## Tech Used
**Server**: Node.js, Express, Mongoose, MongoDB, Cloudinary

**Client**: Flutter, Provider
    
