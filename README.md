# App Demo
<img src="https://github.com/konerunatwar/Making-ML-App-With-Fast-API-And-No-CodeAPP-Using-Bravo-studios/blob/main/ezgif-4-3be53d94f2de.gif" width="200" height="400" />     <img src="https://github.com/konerunatwar/Making-ML-App-With-Fast-API-And-No-CodeAPP-Using-Bravo-studios/blob/main/ezgif-4-81f1fca29a49.gif" width="200" height="400" />     <img src="https://github.com/konerunatwar/Making-ML-App-With-Fast-API-And-No-CodeAPP-Using-Bravo-studios/blob/main/ezgif-4-9e22bd9d1fb1.gif" width="200" height="400" />

# What You Need
1. Your ML Model (Pickle File)
2. Create a Fast API
3. Deploy API to Heroku (This step is free https://www.heroku.com/home)
4. Create a figma account (This step is free https://www.figma.com)
5. Create a bravostudio account (This step is free for 15 days but requires credit card https://www.bravostudio.app)
6. Create a AirTable account (This step is free https://airtable.com)

# Steps 1: Creating an API
first create an Fast API(See File app.py)
* You need to create a airtable account
* Then click on add a base then select start from scratch

  ![step 2](https://user-images.githubusercontent.com/56246430/118486520-5a3d8e80-b737-11eb-9938-4fe13b36528a.PNG)


* Then choose the name
* Now start creating the columns with data you want to get

  ![step5](https://user-images.githubusercontent.com/56246430/118487705-9de4c800-b738-11eb-802e-4fc9e454da18.PNG)


* Click on column 

  ![step4](https://user-images.githubusercontent.com/56246430/118487942-dc7a8280-b738-11eb-8625-0b1c6f0c9c25.PNG)


* Importent: Customize field type then select the name of the column and type of data (ex: Number or Short Text) 

  ![eqwe](https://user-images.githubusercontent.com/56246430/118488670-97a31b80-b739-11eb-8e7e-675d88cd8857.PNG)
 

* Now you need to get your table API to post the data, press help and then go to api documentary 

  ![adasd](https://user-images.githubusercontent.com/56246430/118489633-ad651080-b73a-11eb-9fd2-fdde70d4a622.PNG)
  
 * Now get you post API and API Key and paste it in app.py
  
  ![133123](https://user-images.githubusercontent.com/56246430/118490931-1ef18e80-b73c-11eb-86e9-4af357ff437b.PNG)
  
* We are ready to deploy the API to heroku 
 * Upload the files to Github
 * Use this video to uplode the api file to heroku(https://www.youtube.com/watch?v=H7zAJf20Moc)

# Step 2: Design an app in Figma using bravo studio

* I am giving you the link to my app design (https://www.figma.com/file/HtkalFdmkhwqKqzZJmLBvj/HydRent?node-id=0%3A1)
  
  ![qeqeqe](https://user-images.githubusercontent.com/56246430/118501458-60873700-b746-11eb-81c5-2e352dbea94b.PNG)

* You need to use your credit card to use POST feature it is free for 15 days  
* Here are the tags for bravo studio (https://www.notion.so/Bravo-Tags-Master-List-145bec845f0b4afaa9e3bb8321b218a8)

# Step 3: Create a Database in bravo studio

* select post and past your api
* use https:api.com/docs to get your body
  ![adadsada](https://user-images.githubusercontent.com/56246430/118497170-72ff7180-b742-11eb-9751-ecdb9da671b1.PNG)
* paste the body,JSON in bravo studio
* ![eqweq](https://user-images.githubusercontent.com/56246430/118496737-084e3600-b742-11eb-9302-774f67c87afb.PNG)
* If String "${property_size}"
* if Number ${property_size}
* Importent: all ways  use device ID as same 
* You can test the API by giving parameters keep thekeys same as in body
 
  ![ssASas](https://user-images.githubusercontent.com/56246430/118498052-40a24400-b743-11eb-8cb6-4234d04b9d3f.PNG)
 
 * Now you can use this api for your app
