# angular-photos

/* Steps for the app

app component


another conponent---> can i have a random photo?
                  <--- sure here have you go!



another service---> request to api
                <---- responce from api



some api to fetch random photos



Generate a Service with an appropriate name that will eventually fetch a Photo.



Generate a Component  with an appropriate name that will eventually display a photo + a button



API---> https://unsplash.com/developers
get a random photo
https://unsplash.com/documentation#get-a-random-photo


For API Key create dev account--->\




/*
In the subscription that you added, get acces to the responce and console log it


Try to console log just the url.regualr property



End up with an error from typescript ? Perhaps we need to apply a type annottion to help typescript understand the format of the responce

 */

https://unsplash.com/documentation#creating-a-developer-account
















Take a look at the Unplash API documentation on how to access their API-->https://unsplash.com/documentation#location


https://unsplash.com/documentation#get-a-random-photo


Take a look at the type definition of HttpClient to figure out how to include a headeron the request

Add a new method to the service that will make and return a requrst.








Make Sure the component we just created earlier is visible on the Screen











/* Use Dependancy injection to get access to the service in your component

When the component is about to show on the screen, call the getPhoto method to make the request
--> we have to make subscribtion 


Inspect the request in your network request tab and ensure that you see some data featched
 */






/* Next Step

Add a new propety to the class to store url of the featched image

Store URL from the responce to that propety

Add in a img element in the component templete

Use the property binding symtax to set the 'src' property of the image to the propety you crated in the step #1


 */
