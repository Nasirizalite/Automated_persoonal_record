# Automated_persoonal_record
#!/bin/bash                                                                                                                                   
data=()                                                                                                                                       
data=$(read -p "please enter your first name:")                                                                                               
data=$(read -p "please enter your last name:")                                                                                                
data=$(read -p "please enter your age:")                                                                                                      
data=$(read -p "provide your active email address:")                                                                                          
data=$(read -p "please enter your residential address:")                                                                                      
echo "$data"                                                                                                                                  
echo "$data" >> "$data.txt"                                                                                                                   
edit=$(read -p "Would you like to edit a record?(Y/N):")REPLY                                                                                 
if ["$REPLY" = "Y"];then                                                                                                                      
  echo "Enter the data you want to edit"                                                                                                      
fi
