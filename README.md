# MyPharmacy :
MyPharmacy is an application that helps pharmacies managing their branches and employees along with the customer in a very organized way 

## Features :
1. User Authentication
2. Add your pharmacy details and whereabouts
3. Add branches to your pharmacy
4. Add Employees to any branch in your pharmacy and there are three user types that you can add as a manager 
    - Vendor Manager (manages receiveing products from the vendors and writing an invoice )
    - Employee who is responsible for selling products in the branch and interacting with customers
    - Warehouse Manager who is responsible for managing the products in the warehouse [Still in development]
5. Add Customers to your pharmacy
6. Manage Depts and Returns from customers
7. Write a receipt for the customer and print a PDF copy of it 
8. Add a unique barcode to each receipt and invoice 
9. Scan the products barcode 
10. You can scan the receipt to immediately sell the same products again
11. You can manage expired products either by returning them the the vendor or disposing of them
12. You will get a notification when a product in your branch is almost out 
13. You can see a detailed product report to view information about this product and the branches that sells it
14. You can see a detailed report to view all the sales and returns and the dept informations along with a graph
15. You can view a yearly report of the revenue and the losses of the pharmacy along with a graph for each month
16. You can view information about an employee and see all the sales and purchases they did
17. You can view information about a branch and see all the sales and purchases done from this branch

## Used in this app :
- Architecture :
	- [Lifecycle](https://developer.android.com/jetpack/androidx/releases/lifecycle)
	- [Viewmodel](https://developer.android.com/topic/libraries/architecture/viewmodel)
	- [Retrofit](https://square.github.io/retrofit/)
	- [Firebase Authentication](https://firebase.google.com/docs/auth)
	- [Firebase Realtime Database](https://firebase.google.com/docs/database)
	- [Firebase Cloud Messagin](https://firebase.google.com/docs/cloud-messaging)

- UI :
	- RecyclerView
	- Fragments

- Third party and miscellaneous libraries :
	- [MPAndroidChart](https://github.com/PhilJay/MPAndroidChart)
	- [Android-ProgressViews](https://github.com/zekapp/Android-ProgressViews)
	- [FlexBox Layout](https://github.com/google/flexbox-layout)
	- [ZXING](https://github.com/journeyapps/zxing-android-embedded)
	- [Chip Navigation bar](https://github.com/ismaeldivita/chip-navigation-bar)

## Sreenshot :
### Authentication
<p float="left">                                                                                        
<img src="https://user-images.githubusercontent.com/80918411/131255140-cd80241d-6009-452f-8493-8b8d2f54f64e.gif" width="20%">
<img src="https://user-images.githubusercontent.com/80918411/131254998-2aa23d01-a964-4e73-bda2-df2f5660485c.jpg" width="20%">
<img src="https://user-images.githubusercontent.com/80918411/131255022-069b3f2c-432b-46c4-b0a8-5f9ef99e0c1a.jpg" width="20%">
<img src="https://user-images.githubusercontent.com/80918411/131255029-03c07ce5-155a-494f-ad3a-6212fed97779.jpg" width="20%">
</p>
	
### Inventory 
1. you can swipe on a product to the right to edit its main information or to the left to delete it
2. you can click on a product to see a dialog showing the product information
3. you can filter your inventory by a huge amount of variables
<p float="left">                                                                                        
<img src="https://user-images.githubusercontent.com/80918411/131258820-7802a52f-87a9-49ac-a99b-c4fd3f8950f2.gif" width="20%">
<img src="https://user-images.githubusercontent.com/80918411/131258736-e41f4ecb-a9fd-41f7-90eb-c7f2a728efb1.jpg" width="20%">
</p>

### Sales
#### Adding products to the cart
1. you can add any amount of items to the selected list 
2. if a product is expired you will not be able to add it
3. you will get a notification if the quantity of a product is less than the entered lowest amountto remind you to buyit again
4. a pdf receipt will generate after each sale and it will have a unique barcode 
5. you can scan any receipt barcode to regenerate the receipt immediately
<p float="left">                                                                                        
<img src="https://user-images.githubusercontent.com/80918411/131258926-fad9af3d-6b06-4adf-8b5c-2fbd3935c633.jpg" width="20%">
<img src="https://user-images.githubusercontent.com/80918411/131258925-5c891e8f-6771-49cf-8257-ebf685fc4495.jpg" width="20%">
<img src="https://user-images.githubusercontent.com/80918411/131355475-eb5e9ce8-b8fa-44ff-bb71-d0b4dc6c74ce.jpg" width="20%">
<img src="https://user-images.githubusercontent.com/80918411/131289339-b9d8c366-5919-46c8-95d1-2d8218dbe5a2.png" width="20%">
<img src="https://user-images.githubusercontent.com/80918411/131289324-abee7a34-f358-4a30-aba6-2ddaf5fd8742.jpg" width="20%">
</p>

#### Returning products :
1. You can scan a receipt to return some of its products
2. You can see the return information along with the old products and what you returned from them
<p float="left">                                                                                        
<img src="https://user-images.githubusercontent.com/80918411/131356814-613ef6bb-7a5c-4e8c-80ff-ae15df80bf3e.jpg" width="20%">
<img src="https://user-images.githubusercontent.com/80918411/131356818-b52a557f-a9fd-4484-af40-f528271ae5c3.jpg" width="20%">
</p>


#### Setting the customer or adding a new one
1. when selling the products you can either assign the receipt to an existing customer or create a new one 
2. the customer can pay the entire amount or pay some of it and continue paying later
<p float="left">                                                                                        
<img src="https://user-images.githubusercontent.com/80918411/131258949-b76f6603-5e0f-44f2-89c9-982f190a9bb7.jpg" width="20%">
<img src="https://user-images.githubusercontent.com/80918411/131258950-786c80b0-78ba-4436-b6b0-ead337a9d238.jpg" width="20%">
<img src="https://user-images.githubusercontent.com/80918411/131258947-f0344922-6e04-400c-bc86-fdaeeda689bc.jpg" width="20%">
</p>

### Customers Informations :
<p float="left">                                                                                        
<img src="https://user-images.githubusercontent.com/80918411/131259731-5fb90c1f-4624-40b7-909a-40b112ee2245.jpg" width="20%">
<img src="https://user-images.githubusercontent.com/80918411/131259737-ffef649d-f7dc-4987-8a0e-62e15f864f59.jpg" width="20%">
<img src="https://user-images.githubusercontent.com/80918411/131259729-1bf702dc-6f9f-441b-b923-b2ff2e200113.jpg" width="20%">
<img src="https://user-images.githubusercontent.com/80918411/131259743-f69f9ad7-d634-4f93-bf7f-9fa4f00dd396.jpg" width="20%">
</p>

### Employee Information :
1. You can add a new employee and assign him/her to a branch and give him/her the premission you want
2. You can swipe right to edit the employee information of swipe left to deactivate the employee
3. You can filter the pharmacy employees
4. Click on an employee to see his/her information and the receipts they did
<p float="left">                                                                                        
<img src="https://user-images.githubusercontent.com/80918411/131299465-88b09d51-4be2-48da-9018-1ad4e12167cd.jpg" width="20%">
<img src="https://user-images.githubusercontent.com/80918411/131296082-f8c93065-8200-4e25-a681-57d3353937c7.jpg" width="20%">
<img src="https://user-images.githubusercontent.com/80918411/131296086-59cb07aa-8fe2-4ef0-a9b5-1d7ba83f96b1.jpg" width="20%">
<img src="https://user-images.githubusercontent.com/80918411/131296092-b6304bcd-39e2-40a7-9c87-46da0685d28e.jpg" width="20%">
<img src="https://user-images.githubusercontent.com/80918411/131296095-cb92547f-f7f0-4329-9578-f807de35929a.jpg" width="20%">
</p>

### Branches Information :
1. You can see all the branches and filter them
2. You can add a new branch 
3. You can swipe right to edit the branch information or swipe left to deactivate it
4. Click on a branch to see its information and its receipts
5. Filter receipts by setting a date range
<p float="left">                                                                                        
<img src="https://user-images.githubusercontent.com/80918411/131314033-bb4978fe-b8a6-4278-8575-eb394abed35c.jpg" width="20%">
<img src="https://user-images.githubusercontent.com/80918411/131314038-7df96c55-4e8e-42d7-a9bd-742239e6412d.jpg" width="20%">
<img src="https://user-images.githubusercontent.com/80918411/131314030-ed663b98-e3f7-44b5-b320-8a61d7eb0c22.jpg" width="20%">
</p>

### Vendors Information :
1. You can see all the vendors how have contracts with the pharmacy
2. You can add vendors
3. You can swipe right to edit the vendor information of swipe left to deactivate him/her
4. You can receive products from the vendor
5. You can click on a vendor to see his/her information along with the invoices they did
6. You can click on an invoice to see its information and its products
<p float="left">                                                                                        
<img src="https://user-images.githubusercontent.com/80918411/131356202-04ed2345-75ea-4c50-bcba-2211f1a05483.jpg" width="20%">
<img src="https://user-images.githubusercontent.com/80918411/131356207-45f87fd7-1fcf-48c4-a361-5260e6b21597.jpg" width="20%">
<img src="https://user-images.githubusercontent.com/80918411/131356213-2eb43a6d-b677-4bbb-8e4e-be4de4156781.jpg" width="20%">
<img src="https://user-images.githubusercontent.com/80918411/131356220-386f1622-b106-4782-91ef-40271d022f94.jpg" width="20%">
<img src="https://user-images.githubusercontent.com/80918411/131356223-e1b3736a-1355-4045-86f1-8215100d9664.jpg" width="20%">
<img src="https://user-images.githubusercontent.com/80918411/131356228-5c1d1b67-2250-4696-b663-d9f48ecba5de.jpg" width="20%">
</p>
