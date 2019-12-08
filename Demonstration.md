In the following section, I will step by step demonstration how a small organization or individual user can utilize Airtable to manage their data which is a relatively small collection. Here I use 2014 hksmff screening activity materials as a sample collection.  

In the repository, you will find the [2014_hksmff_basic_inventory](https://github.com/jyw321/Airtable_Exercise/blob/master/2014_hksmff_basic_inventory.csv) in a .csv file as the original raw file for Airtable importation. For the sake of demonstrating more functions, I changed some contents of the original records as shown on the hksmff website. At the end of this demonstration, you will find the link to the work base I created. 

**Content**

* [Demo 1: Get started](https://github.com/jyw321/Airtable_Exercise/blob/master/Demonstration.md#demonstration-1-start-an-account-and-import-your-own-spreadsheet)
* [Demo 2: Beautify your work](https://github.com/jyw321/Airtable_Exercise/blob/master/Demonstration.md#Demonstration-2-Edit-and-beautify-your-base)
* [Demo 3: Choose your view](https://github.com/jyw321/Airtable_Exercise/blob/master/Demonstration.md#Demonstration-3-Choose-your-own-view)
* [Demo 4: Build relations](https://github.com/jyw321/Airtable_Exercise/blob/master/Demonstration.md#Demonstration-4-Build-relations-between-tables-and-records)


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

***

### Demonstration 2. Edit and beautify your base

A common problem encountered by different archives is the multi-language embedded in the materials. In this case, Chinese and English are both used in each item. A disadvantage of Airtable is that language other than English is not recognized by Airtable at first place. In this case, you will need to fill and edit the cells manually to correct the language.
![language not shown](https://github.com/jyw321/Airtable_Exercise/blob/master/Image_7.png)

After language correction, we can proceed to refine the fields so that more functions could be executed. From here, we convert the nature of fields into different types. 

***

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
6. By clicking Save, you will see all the places of origin are converted to colorful "tags"

![choose duration type](https://github.com/jyw321/Airtable_Exercise/blob/master/Image_10.png)

*Caution: In the .csv file, remember to use comma to separate multiple values in one cell, so that Airtable can recognize. This is because of the language Airtable uses -JSON.*

***

The advantage of doing such conversion is for conducting grouping. Here I again take the place of origin as an example.

1. Go to the “Place of origin” field
2. Pull down the menu bars by clicking the arrow
3. Choose “Group by this field”
4. As a result, you will see films are organized by places of origin

![choose duration type](https://github.com/jyw321/Airtable_Exercise/blob/master/Image_11.png)

Taking advantage of the “Multiple select” function, I will convert more fields into this type for more grouping options. For example, grouping by filmmaker, film series, language, subtitle, color mode, year of production, and so on is exceptionally useful to AV archives.

*Caution: When applying the “Multiple select” function, chances are you would see “duplicated” tags. One very possible reason is that you or your collaborators mis-spelled words in one cell (e.g. in one cell, you spell Chinse instead of Chinese). Airtable would not automatically correct for your or merge those records. Instead, if you encounter this situation, you need to find out the mis-spelled word and correct it before applying the “Multiple selection” function to avoid duplicated but invalud tags.*

***

### Demonstration 3. Choose your own view

Archivists sometimes face tables that are super wide because of the large number of fields. Instead of keep rolling the bars from left to right to view those at the tail, Airtable provides an easy-to-use function to serve this purpose.  

1. On the top left side, there is a button called “Hide fields”
2. Click “Hide fields”, then click “Hide all”
3. Turn the fields you want to view back on

Furthermore, you can **share a “view” of the table** which contains only the fields you want to show. It is beneficial when you need to demonstrate only the basic information of your collection to external visitors.

1. Based on the previous steps, now the table only shows a limited number of fields
2. At the top right of the table, you will find a “…” icon. 
3. Click the “…” icon, choose “Duplicate view”

![Duplicate view](https://github.com/jyw321/Airtable_Exercise/blob/master/Image_12.png)

4. Rename the view. I name this new view as “Limited View”

![Rename view](https://github.com/jyw321/Airtable_Exercise/blob/master/Image_13.png)

5. At the top left of the table, choose the “Limited View”. Now you see your screen shows the table with limited fields only

![Choose limited view](https://github.com/jyw321/Airtable_Exercise/blob/master/Image_14.png)

6. Click the oval “SHARE” button on the top right side of the table

7. Scroll down for the box “Create a shared view link”

8. Click “Share the current view”

9. Click “Create a shareable grid view link”

[Example of a limited view sharing](https://airtable.com/shr2z2rNzYjnNNYEQ)

***

You can also choose to **share your whole base**. You can invite collaborators through sending email invitation, and sharing a private link. If you only want to show the outcomes, you can also create a link that only shows the view-only work base.

1. Click the oval “SHARE” button on the top right side
2. Scroll down for the box “Create a shared link to the whole base”
3. Click “Private read-only link”
4. Choose how you would like your readers to edit or copy your data 
5. You can also preview the shared link

***

### Demonstration 4. Build relations between tables and records

One of the highlights of Airtable is its convenience of building record relation, so that users do no need to shuffle from table to table to track a particular record. 

To demonstrate this function, first I need set up a new table within the same base. I name this new table "Screening activity" I will start this table from scratch. This table documents the screening schedule of 2014 social movement film festival, and the data is originated from the hksmff [website](https://smff2014.wordpress.com/film-event/).

1. Create a new table and name it “Screening activity” 

![New table screening activity](https://github.com/jyw321/Airtable_Exercise/blob/master/Image_15.png)

2. Name the fields accordingly: Date, Screening film, Time, Venue, etc. Here I also make some new fields up for demonstration

3. Follow the steps in [Demonstration 2](https://github.com/jyw321/Airtable_Exercise/blob/master/Demonstration.md#demonstration-2-edit-and-beautify-your-base) and choose the appropriate nature for different fields. Here I set the “Date” field into “Date”, the “Time” field into “Single select” and the “Venue” field into “Single select”. 

4. The table could eventually look like this.

![Draft new table](https://github.com/jyw321/Airtable_Exercise/blob/master/Image_17.png)

*Attention: you can write the text directly in the cells first and then convert the type of the field. Or you can first set the field type, name the options into different venues, and then in every cell, you simply “single select” the venue.* 

![Name the options](https://github.com/jyw321/Airtable_Exercise/blob/master/Image_16.png)

***

Now let’s set the type for the field “Screening films” to enable the relational function.

1. Customize the field into “Link to another record”

![Customize link to another record](https://github.com/jyw321/Airtable_Exercise/blob/master/Image_18.png)

2. Choose “2014 films” as the related table 

![link to table](https://github.com/jyw321/Airtable_Exercise/blob/master/Image_19.png)

3. Now this field is linked to the table “2014 films”

4. When you click each cell under the field “Screening films”, you will see a “+” icon. Click the “+” icon then you are allowed to select which film(s) will be shown on that date.

5. By clicking the film in the “Screening films” cell, an expanded view will be shown. On this expanded view, you can look into the details of that film. You will also find a curve line on top of this expanded view, indicating the origin of the record.

![link to records](https://github.com/jyw321/Airtable_Exercise/blob/master/Image_20.png)

6. You can create tables that collate information on human resource, equipment needs, and so on. Following the above steps, you can link the “Screening activity” to more tables and records.

![create more tables](https://github.com/jyw321/Airtable_Exercise/blob/master/Image_21.png)

***

#### Now the work base looks cool, right? 

#### Ready to build up your own work base?

**I share the Airtable “view” of the hksmff exercise base here for your reference. Anyone can view (but not edit) this base with [this read-only link](https://airtable.com/shrrZWNe9zmVwptK8)** 
