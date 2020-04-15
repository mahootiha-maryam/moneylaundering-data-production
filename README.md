# moneylaundering-data-production
This project is related to the beginning of my master's thesis. It has been supported by Dr. Alireza Hashemi Golpayegani and Dr. Babak Sadeghian at Amir Kabir University, Department of Computer Engineering and Information Technology.
Banking data is a secret data that is hard to access anywhere in the world. My master project is to detect money laundering by SNA method. I needed bank data, but I realized it was due to lack of access. I need data simulation to be such data.
In this simulation, both the production of fraudulent data and the production of non-fraudulent data are considered. Attempts have been made to simulate all aspects of fraudulent and non-fraudulent practices, and finally to provide a relatively complete simulator.
My simulation is based on three processes of money laundering in financial transactions:1)Money placement 2) Money layering 3) Money integration
In simulating each of these processes, I have considered a rule. Rule 1 relates to the cashing in and Rule 2 and 3 relates to the transferring.
An important feature of this simulator is that it is flexible and produces data with different parameters.
Instructions:
1.Remove the folder from zip. Enter folder and execute MLD.exe. wait 5 seconds to lunch the program.
2.Read the basic instructions and click the Next button
3.The first field in the first line asks you how much you want to have fraudulent data due to the placement of money.
4.The second field in the first line asks you how much you want to have fraudulent data due to the layerring of money
5.The third field in the first line asks you how much you want to have fraudulent data due to the integration of money
6.The first field in the second line asks you according to the law of a particular bank, how much money for cashing in is considered money laundering.
7.The second field in the second line asks you according to the law of a particular bank, how much money for transferring is considered money laundering.
8.The first field in the third line asks you according to the bank, how much is high for cashing in, but not considered as money laundering.
9.The second field in the third line asks you according to the bank, how much is high for transferring, but not considered as money laundering.
10.The first field in the fourth line asks you about the start range of time that these events occur.
11.The second field in the fourth line asks you about the end range of time that these events occur.
12.Fifth line asks you about the number of non-fraudulent cashing in data. Due to the calculation of normal data types, this number must be greater than forty.
13.Sixth line asks you about the number of non-fraudulent transferring data. Due to the calculation of normal data types, this number must be greater than eighty.
14.After clicking Done, your data will be stored in the D folder with the file in which the all of the persons who are guilty and colleagues of them are labeled. If you leave the data blank or do not pay attention to its format, you will encounter an error.
This program is published with Python code and using Pandas library.

