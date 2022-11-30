# DADS5001 Quiz1: Nosql data management

## Develop a NoSQL-data management app (pymongo + mongodb)

By: Nithida Phookriangkrai (student id: 6420422004)

Link to video presentation: https://www.youtube.com/watch?v=jqnxt_XXIKI

Link to source code: https://github.com/pnithida/DADS5001_Quiz1_6420422004/blob/main/6420422004_Quiz1_StockManagement.ipynb

GUI app for Clothing inventory management using Tkinter. The app has CRUD functions along with visualization

<img width="1084" alt="Screenshot 2565-11-29 at 23 47 43" src="https://user-images.githubusercontent.com/56344603/204591104-58e5e39e-c770-4096-89cd-1945047f4dcf.png">

In MongoDB, the document contains 1) ID 2) Item 3) Colour 4) Size and 5) Quantity 

<img width="1428" alt="Screenshot 2565-11-30 at 00 04 11" src="https://user-images.githubusercontent.com/56344603/204594887-10e1464c-81a1-485d-b84b-6f473979c5fc.png">

## Starting with GUI app

Note that the Stock ID is automatically generated. So User can CREATE data by key product name in the white box for "Item".

Next, colour and size can be selected from the drop-down list. Then, user has to key quantity of each product and press "Save" button.

Here, user just add blue crop top with size M and quantity is 9 to the collection

<img width="1105" alt="save1" src="https://user-images.githubusercontent.com/56344603/204694977-2220f9f1-fefb-4ade-aa33-4ada7cdae938.png">

The app will READ by find all from the collections and show in the table. The lastest data that user just press save will show in the lowest row (Item ID 10)

<img width="1108" alt="save2" src="https://user-images.githubusercontent.com/56344603/204695071-fa888379-4838-4a71-ad63-5e9a2edd0c0c.png">

If user want to UPDATE any item, user can click on any box in the row and change the data befor pressing "Update" button.

Below figure shows that user will change quantity from '9' to '10'. Now, it shows quantity '9' for Item ID 10.

<img width="1108" alt="update1" src="https://user-images.githubusercontent.com/56344603/204695105-9e990953-9c4b-42ac-a35f-8abd4c01da10.png">

After user press update, the data will be changed to '10' and app will RETREIVE the latest collections and show in the table

<img width="1109" alt="update2" src="https://user-images.githubusercontent.com/56344603/204695124-368c44cc-01b9-405c-8b77-850873099fd3.png">

User can delete the unwanted row by click on any box in the row and press "Delete" button. 

Below figue shows that user will delete Item ID 5.

<img width="1109" alt="delete1" src="https://user-images.githubusercontent.com/56344603/204695159-62f4f5c8-4ad0-4694-8e54-430e2e313f4f.png">

After user press, row of Item ID 5 is gone.

<img width="1102" alt="delete2" src="https://user-images.githubusercontent.com/56344603/204695177-8e8f77e3-75b2-46a6-8109-90b05d2e390e.png">

User can also view a bar graph represent the amount of each product by pressing "Graph" button.

<img width="1102" alt="graph1" src="https://user-images.githubusercontent.com/56344603/204695196-9cef02be-090c-44fc-bf41-ec9c22b11274.png">

The latest data will show up. Each bar will show ID_Item_Colour_Size on the x-axis while the y-axis will show the quantity of each product.

<img width="613" alt="graph2" src="https://user-images.githubusercontent.com/56344603/204695215-bbc2fc2f-9852-418a-9e8d-a4d8801415e7.png">
