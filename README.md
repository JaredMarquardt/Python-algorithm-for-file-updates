# Python-algorithm-for-file-updates
The following algorithm is used to open, read, and update a file ("allow_list.txt"). This file contains a list of IP addresses that are allowed to access restricted content.

# Initial setup:
![Open the file](https://i.imgur.com/NQfykUu.png)

Initially, a variable is created to hold the name of the file we will be updating. 
Additionally, another variable is created to store the list of IPs to be removed. 
This is where our file opening command begins.

# Read the file contents:
![Read the file](https://i.imgur.com/NcftaX8.png)

After opening and reading the file we save it to a variable named ip_addresses and its contents are printed.
Output below:

![Read the file2](https://i.imgur.com/pHSa3fw.png)

# Convert the string into a list:
![ConvertString](https://i.imgur.com/hufusfF.png)

Use ".split()" to convert the string in ip_addresses to a list. Output below:

![ConvertString2](https://i.imgur.com/1ZMGwbF.png)

# Iterate through the remove list:
![Iterate](https://i.imgur.com/Y07DkiD.png)

Using a for loop to cycle through each element in remove_list. Output below:

![Iterate2](https://i.imgur.com/jwRj72K.png)

# Remove IP addresses that are on the remove list:
![Iterate](https://i.imgur.com/0tn6EEd.png)

Now an if statement is added to the for loop. Using .remove() the IPs in remove_list are eliminated. Output below:

![Iterate2](https://i.imgur.com/Aq1k3LK.png)

# Update the file with the revised list of IP addresses:

![Update](https://i.imgur.com/tGl5z3D.png)

Finally it's time to update the file with the new list of allowed IP addresses. The file is reopened, then written over.

# Conclusion:
This lab taught me how to open files and edit them using the various commands showcased above.
