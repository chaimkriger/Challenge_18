# Creating A Blockchain

In this application, I build a blockchain-based ledger system, complete with a user-friendly interdace. This ledger should allow partner banks to conduct financial transactions and to verify the integrity of the data in the ledger.

Here is an overlay of the steps I took to create this application.

First, I create a new data class named "Record". This class will serve as the blueprint for the financial transaction records that the blocks of the ledger will store. Inside of this dataclass I include a formulized data structure that includes the sender, reciever, and amount attributes.

Next, I change the pre existing "Block" data class by replacing the generic data attribute with a "record" attribute that's a type of data.

Finally, I create additional user input areas in the Streamlit application. These input areas collect the relevant information for each financial record that I store in the Pychain ledger, such as the sender info, the reciever info, and the amount.

--- 

What is Streamlit? Streamlit tue=rns data scripts into shareable web apps in minutes. All in Python. Below is a screenshot of the blockchain application when launched on Streamlit

![screenshot of Streamlit Blockchain app](https://raw.githubusercontent.com/chaimkriger/Challenge_18/main/Screenshot%20(79).png)

## Technologies

This project leverages Python 3.7, and Streamlit

---

## Installation Guide

Before running this application, Python must be installed. The user can install Streamlit by simply oprning the desired enviroment, and typing "!pip install streamlit"

---

## Usage

Navigate to the directory where pychain.py is located and run the file by typing streamlit run pychain.py in the command line. The user is free to add additional input messages to the code, or make any edits deemed necessary.

---

## Contributors

Just me, and a little bit of help from module 18

## License

No license, feel free to copy the code any time.












