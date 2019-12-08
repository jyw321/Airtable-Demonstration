In the following section, I will step by step demonstration how a small organization or individual user can utilize Airtable to manage their data which is a relatively small collection. Here I use 2014 hksmff screening activity materials as a sample collection.  

In the repository, you will find the [2014_hksmff_basic_inventory](https://github.com/jyw321/Airtable_Exercise/blob/master/2014_hksmff_basic_inventory.csv) in a .csv file as the original raw file for Airtable importation. For the sake of demonstrating more functions, I changed some contents of the original records as shown on the hksmff website. At the end of this demonstration, you will find the link to the work base I created. 

### Demonstration 1. Start an account and import your own spreadsheet

You can create your own account on Airtable, or you can simply use your Google account.
![Create an account](https://github.com/jyw321/Airtable_Exercise/blob/master/Image_5.png)

Once you log in Airtable, you will see that Airtable has prepared some templates for you to start with based on your own needs (refer back to Img. 1). But you can always start from scratch or import your own spreadsheet to kick off a work base. 

1. On the “My First Workspace” interface, click “Add a base”
2. Choose “Import a spreadsheet”

*(remember to save your original spreadsheet as .csv file)* 

3. Import the .csv file
4. Name and choose the style of this base (pick any color and icon you like!)
5. After the original .csv file is successfully imported, name the table “2014 films”

![Name and stylish your base](https://github.com/jyw321/Airtable_Exercise/blob/master/Image_6.png)

### Demonstration 2. Edit and beautify your base

A common problem encountered by different archives is the multi-language embedded in the materials. In this case, Chinese and English are both used in each item. A disadvantage of Airtable is that language other than English is not recognized by Airtable at first place. In this case, you will need to fill and edit the cells manually to correct the language.
![language not shown](https://github.com/jyw321/Airtable_Exercise/blob/master/Image_7.png)

After language correction, we can proceed to refine the fields so that more functions could be executed. From here, we convert the nature of fields into different types. 

A powerful function of Airtable is the automatic calculation of time duration of multiple AV materials. Most of time, facing a large number of video materials which have different durations of time, archivists have difficulties to calculate the total duration of this collection. In Airtable, the “Duration” type of field can solve this problem. 

1. Go to the “Duration” field	
2. Pull down the menu bars by clicking the arrow
3. Choose “Customize field type”

![customize field](https://github.com/jyw321/Airtable_Exercise/blob/master/Image_8.png)

4. At the blue bar, choose “Duration” type and pick a format (e.g. h:mm)

![choose duration type](https://github.com/jyw321/Airtable_Exercise/blob/master/Image_9.png)

5. By clicking Save, you will see all the duration of time are converted to “real” duration of time. 
6. At the bottom of this field, you will find a total duration of time. In this case, the total duration is 109 hours and 53 minutes.
***

Another function which I find very useful is converting cells in which multiple values are included to a “multi-choice-like” appearance. This function largely facilitates you to group and filter the data based on different needs. 

Here I take the field “Place of origin” as an example. 
1. Go to the “Place of origin” field
2. Pull down the menu bars by clicking the arrow
3. Choose “Customize field type”
4. At the blue bar, choose “Multiple select” type 
5. Immediately, you will see the places of origin are shown under the blue bar. These are the “multiple selections” automatically created by Airtable
6. By clicking Save, you will see all the places of origin are converted to colorful tags

![choose duration type](https://github.com/jyw321/Airtable_Exercise/blob/master/Image_10.png)

*Caution: In the .csv file, remember to use comma to separate multiple values in one cell, so that Airtable can recognize. This is because of the language Airtable uses -JSON.*

***


