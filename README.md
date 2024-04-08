# Inventory-Management-System
This is an Inventory management system 
How to Setup


  1. Clone Project
   
     git clone https://github.com/Gayatri2890/inventory-management.git


 

 2.Go To Project Directory
   
    cd inventory-management


   
 3.Create Virtual Environment
 
    python3 -m venv venv



    
 4. Active virtual Environment
   
      source venv/bin/activate




  5.Install Requirements File
    
    pip install -r requirements.txt



  6. Migrate Database
     
     python manage.py migrate




 7.Create Super User
    
     python manage.py createsuperuser




  8. Run Project

      python manage.py runserver
