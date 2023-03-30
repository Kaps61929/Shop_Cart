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


# Demo








https://user-images.githubusercontent.com/115138974/228749240-b8cd3491-4a8d-470c-aa55-5b95e224ddd7.mp4







**User Pannel**


















https://user-images.githubusercontent.com/115138974/228749020-c7f47736-0370-4025-8af6-86e4ac190bdf.mp4











**Admin Panel**

# ScreenShots
<p float="left">
<img src="https://user-images.githubusercontent.com/115138974/228755029-b37d646d-f571-4360-a936-ba20cc7ca5b9.jpg" height ="400" width ="200">
<img src="https://user-images.githubusercontent.com/115138974/228755050-103934c9-eb5e-479c-89d6-4940171bb248.jpg" height ="400" width ="200">
<img src="https://user-images.githubusercontent.com/115138974/228757329-262cb3fc-48aa-41b7-a03b-820949f9ace9.jpg" height ="400" width ="200">
 <img src="https://user-images.githubusercontent.com/115138974/228757649-ec52e812-97fb-407b-97b0-7e2b6ff9e06f.jpg" height ="400" width ="200">
 <img src="https://user-images.githubusercontent.com/115138974/228757668-26211d7e-585a-415e-a0f0-a3c593afe2f6.jpg" height ="400" width ="200">
 </p>




## Running Locally
After cloning this repository, migrate to ```flutter-amazon-clone-tutorial``` folder. Then, follow the following steps:
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
    
