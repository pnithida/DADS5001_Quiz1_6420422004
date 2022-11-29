# DADS5001 Quiz1: Nosql data management

## Develop a NoSQL-data management app (pymongo + mongodb)

By: Nithida Phookriangkrai (student id: 6420422004)
Link to video presentation: 


GUI app for Clothing inventory management using Tkinter. The app has CRUD functions along with visualization

<img width="1084" alt="Screenshot 2565-11-29 at 23 47 43" src="https://user-images.githubusercontent.com/56344603/204591104-58e5e39e-c770-4096-89cd-1945047f4dcf.png">

In MongoDB, the document contains 1) ID 2) Item 3) Colour 4) Size and 5) Quantity 

<img width="1428" alt="Screenshot 2565-11-30 at 00 04 11" src="https://user-images.githubusercontent.com/56344603/204594887-10e1464c-81a1-485d-b84b-6f473979c5fc.png">

## Starting with GUI app

Note that the Stock ID is automatically generated. So User can CREATE data by key product name in the white box for "Item".

Next, colour and size can be selected from the drop-down list. Then, user has to key quantity of each product and press "Save" button.

ใส่รูปกรอบแดง save

The app will READ by find all from the collections and show in the table

ใส่รูปกรอบแดง table

If user want to UPDATE any item, user can click on any box in the row and change the data befor pressing "Update" button.

The data will be changed and app will RETREIVE the latest collections and show in the table

ใส่รูปกรอบแดง update

User can delete the unwanted row by click on any box in the row and press "Delete" button. The delete row will be gone.

ใส่รูปกรอบแดง delete

User can also view a bar graph represent the amount of each product by pressing "Graph" button.

The latest data will show up. Each bar will show ID_Item_Colour_Size on the x-axis while the y-axis will show the quantity of each product.
