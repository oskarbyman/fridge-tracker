# fridge-tracker
A course work for the Distributed Systems 2022 course from the University of Oulu.

## Description
The main idea is to develop a three part system that consists of a user application, database application and a watcher application

### User app
Main features are:
1. Enter food picture/name and expiry date
2. Receive alerts of products expiring or already expired
3. Create a default-configuration of the fridge, i.e. save the current contents to a shopping list
4. Check the quantities of the fridge.
5. Save a minimum quantity of food supplies before alert is sent

### Database app
Main features are:
1. Store data input from the user app
2. Enable the watcher to check expiry dates

### Watcher app
Main features are:
1. Check the expiration dates once per day
2. Check the contents once per day
3. Send alerts to the user app if food is expiring or minimums are met
