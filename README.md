# Excel-ionapi

Clone or download the repository in a local folder

go to the folder

![image](https://user-images.githubusercontent.com/22134155/44097800-e64fa318-9fde-11e8-9945-c57393f53fbf.png)

Double click on each of the files

## Demo-V2.0.xlsm

if you have the macro disabled click to enable it

![image](https://user-images.githubusercontent.com/22134155/44098532-bb21b38c-9fe0-11e8-95c0-9b19f3367485.png)

open the ionapi file that you have downloaded from Infor OS when you have registered the backend service

![image](https://user-images.githubusercontent.com/22134155/44098995-e3d1f2f0-9fe1-11e8-96be-67d21876f335.png)

copy the corrisponding values into the excel cells excepts the endpoint

![image](https://user-images.githubusercontent.com/22134155/44099127-33e18f8a-9fe2-11e8-98b6-5291b63efdbd.png)

click the Get User Data button and the application will reply with a dialog box showing the user details data 

![image](https://user-images.githubusercontent.com/22134155/44099366-c2406486-9fe2-11e8-929e-a56a25fd80be.png)

when you click ok, If some value is blank you get a warning...

![image](https://user-images.githubusercontent.com/22134155/44099484-08e4c6e8-9fe3-11e8-912a-86460b1f355f.png)

Click OK and the cells will be populated with that data.

![image](https://user-images.githubusercontent.com/22134155/44099531-23e07906-9fe3-11e8-9dc7-c8571e15d922.png)

___

## Excel-API-OAuth2 - V2.0 - M3.xlsm

if you have the macro disabled click to enable it

![image](https://user-images.githubusercontent.com/22134155/44098532-bb21b38c-9fe0-11e8-95c0-9b19f3367485.png)

click on the Reset button to clear all cells excepts the endpoint

![image](https://user-images.githubusercontent.com/22134155/44100928-70741220-9fe6-11e8-8a54-f7b3afc88df6.png)

replace the value 71250 with the code for the customer you want to display the details with

click on the Load Profile button and a dialog box will open.
Go to the folder where you have saved the ionapi file that you have downloaded when you have registered the webapp
and select one file a click open

![image](https://user-images.githubusercontent.com/22134155/44101873-b25b8fae-9fe8-11e8-97da-7be0d04afb78.png)

if the file doesn't contain the value for the Redirect URL property a warning will appear

![image](https://user-images.githubusercontent.com/22134155/44102049-182fcb42-9fe9-11e8-9f71-09b847acde98.png)

click OK and fill manually the value.
you can find that value going to the IONAPI registry and open the registered app

![image](https://user-images.githubusercontent.com/22134155/44102164-5e9a1ce0-9fe9-11e8-9522-1980cfb1d354.png)
![image](https://user-images.githubusercontent.com/22134155/44102394-da057596-9fe9-11e8-948f-2bf46e004026.png)

once you have filled the value in the cell than the button will enable

![image](https://user-images.githubusercontent.com/22134155/44106135-0a1877b0-9ff4-11e8-9091-645d3576e6ec.png)

click the get token button to open a browser for authentication

![image](https://user-images.githubusercontent.com/22134155/44106233-5ff746ca-9ff4-11e8-94fd-6d10343a6448.png)

provide your credential and click the allow button to retrieve the token needed for calling the ionapi

![image](https://user-images.githubusercontent.com/22134155/44106306-92c2a266-9ff4-11e8-95f5-3982dc915952.png)

the browser will close and the response is displayed in the cell

![image](https://user-images.githubusercontent.com/22134155/44106360-b8d2a456-9ff4-11e8-8170-903a27f374e1.png)

click the Get User Data button now to make the ionapi call for getting the customer details.
the data are displayed into the cells

![image](https://user-images.githubusercontent.com/22134155/44106462-0ad0b23e-9ff5-11e8-839e-ee3f67a99291.png)

If you want to refresh the token you can click on the Refresh Token button and the result is displayed beside the Token cell

![image](https://user-images.githubusercontent.com/22134155/44106599-6562d84e-9ff5-11e8-804c-a040b6f534d1.png)

___

## Excel-API-OAuth2 - V2.0.xlsm

For this example follow the same steps you did for the example above.
instead of the customer data it will display the user details

see the result below

![image](https://user-images.githubusercontent.com/22134155/44106828-f6ad5bf8-9ff5-11e8-8cb8-9d110cea8603.png)

clicking on the Revoke Token the current token expires and you need to get a new token for calling the api

![image](https://user-images.githubusercontent.com/22134155/44106935-3abb014c-9ff6-11e8-9196-c36c22e1227f.png)

 






