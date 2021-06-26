# task 2 robot

## Contents
*  *dataBase.sql*: contain the database with two tables for arm and base.
*  *Gui.php*; The front end control of the robot .
*  *angles.php*: A file that retieves arm angles's values from database.
*  *direction.php: A file that retrieves base direction and movement status from database. 
*  *style.css*: The main style for the GUI.
*  *script.js*: The main script for the GUI.

## How To Use our GUI
### Arm
It contains **6** bars each one of them will  adjust a single engin's angle , these bars may differ in upper and lower bounds.
After adjusting angles you can click on either **save** or **operate** buttons, save button will save the settings you have chosen to database, and operate button will do the same including applying these settings to the robot arm engins.

### Base
It consist of **5** buttons [forward, left, right, stop backward], when a button is clicked base of the robot will be moved to the direction of that button.
Down at the south will display movement status.

## How to fetch robot data
* **Arm data** : all you need to do is to access the *angles.php* which contains the data.
* **Base data** : all you need to do is to access the *direction.php* which contains the data. 
