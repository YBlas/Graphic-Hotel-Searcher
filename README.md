**Welcome to the new version of the ultimate Hotel searcher.**

# Basic Guide

This time we are trying to make a more intuitive and accesable programm at the user and developer level.
The final object is to be able to change every setting and have total control of the programm through graphic menu's.

For now the prime realised objectives have bean:
    **1.** Total acces to the data with txt files.
    **2.** Basic Graphic Menu
    **3.** Optimice basic methods
    
# TXT editing guide
  Every txt whill be generated with the internal methods but you can also make then the hard way through your file explorer.
  
  **Hotel method**
  
    name "hotel name" 
    
    distance float_with_the_distance_to_the_center_of_the_city
    
    pool boolean(string "true" or "false")
    
    city "city name"
    
    wifi boolean(string "true" or "false")
    
  **Description**
    
    The whole txt file assign the description String
    
  **Room method**
  
  // The room method can be exucuted with a previous hotel methos or not, any of the ways it will create all the necessary data.
    
    name "room name"
    
    price float
    
    smoke boolean(string "true" and "false")
    
    capability int_number_of_persons
    
  **busy**
    
    save all the busy dates of a room with the LocalDate sintaxs yyyy-mm-dd
    
  **comments**
    
    array of int numbers with the values of the guest reviews