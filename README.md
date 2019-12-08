# Airtable_Exercise
## Intro to Airtable and Exercise Demonstration
### Airtable for Small-Scale Moving Image Collection - An example of hong kong social movement film festival

*This is also an assignment submitted to the CINE-GT 1808 Digital Literacy course, Fall 2019 NYU.*
*Special thanks to Pamela Vizner's well-planned guidance in this course.*

In this project, I introduce a data management tool called Airtable, which is suitable for organizational or individual users. This is a tool friendly those people with little coding experience. 

In the GitHub repository, besides a step-by-step [demonstration](https://github.com/jyw321/Airtable_Exercise/blob/master/Demonstration.md), you will also find the raw data [inventory sheet](https://github.com/jyw321/Airtable_Exercise/blob/master/2014_hksmff_basic_inventory.csv) based on which I did the Airtable exercise, and a document about [basic concepts](https://github.com/jyw321/Airtable_Exercise/blob/master/Some%20Basic%20Concepts%20of%20Airtable.md). **The goal of this project** is: you can utilize the raw data to get familiarized with Airtable by following the steps in the documentation. In this process, you can have some knowledge on the pros and cons of the tool, so that in the future you can create your own work base.

I am going to use the audiovisual (AV) collection of a Hong Kong-based non-governmental organization (NGO) – hong kong social movement film festival (hksmff) , to demonstrate how a small organization or individual users can utilize Airtable to conduct systematic yet versatile collection management.

The data used for demonstration in this project is derived from hksmff’s home weblog – documentary films shown in their yearly film festival and screening schedules. I will use the film festival in 2014 as an example. I pick this year for some reasons: places of origin of the films are multiple, so that languages of films varied; special characters are included in film titles; some films are derived from film series. Due to the relative complexity of this year, I can demonstrate how to solve these problems on Airtable, which I believe, are also common problems encountered by small organizations. 

The data of [hksmff](https://smff2014.wordpress.com/film-event/) is open to the public, in both Chinese and English languages.

### History of Airtable
Airtable is an online collaboration service headquartered in San Francisco. It was founded in 2012 by Howie Liu, Andrew Ofstad, and Emmett Nicholas. On Airtable’s [homepage](https://airtable.com/about), the team cheerfully express their mission is “to democratize software creation by enabling anyone to build the tools that meet their needs. Creators and creatives around the world use Airtable to do everything from cattle tracking to filmmaking”.

By now, there are already more than 15 million work bases created on Airtable, and more than 80,000 companies use Airtable. Among the thousands of Airtable users, famous names include Tesla, WeWork, Cole Haan, Expedia, BuzzFeed, and so on. In May 2018, Airtable became one of Silicon Valley's sleeper hits, raised $52 million in new funding in a round led by Caffeinated Capital and CRV to bring its total to [$62.6 million](https://www.businessinsider.com/airtable-ceo-howie-liu-interview-on-52-million-in-funding-2018-3). Now, investors include Benchmark, Thrive Capital, CRV, Caffeinated Capital, and Coatue Management. 

The secret to Airtable's success, according to its CEO, [Howie Liu](https://www.businessinsider.com/airtable-ceo-howie-liu-interview-on-52-million-in-funding-2018-3), is the fact that every cell of a spreadsheet can store anything, including photos and lists. “We think we can be what Windows was for personal computing,” he said. “We're confident we can be the Apple or Microsoft of the low-end-app space.”  

Generally speaking, Airtable is a combination of spreadsheet and database on a colorful Excel-like or Google Form-like interface. 
![colorful interface of Airtable](https://github.com/jyw321/Airtable_Exercise/blob/master/Image_2.png)

Nowadays Airtable is not only suitable for sizable corporations to manage different sorts of data and workflows, but also a friendly tool for small organizations and even individual users to conduct data management. 
![Multiple functions could be achieved by Airtable](https://github.com/jyw321/Airtable_Exercise/blob/master/Image_1.png)

### A Friendly Tool
Below are main features that I think are beneficial to small organizations and individual users whose collection is consisted of less than 1,200 items in each collection.

**Easy to register**: simply by linking your Google account with Airtable, an account is generated. No need to register a separate Airtable account.

**Cloud-based interface**: users do not need to install any software to use Airtable. Because of this cloud-based nature, every action is automatically saved even you forget to click the "save" button.

**Technical requirement**: No coding experience from users is needed. The interface of Airtable is Excel or Google Form alike.

**Low cost**: Even though Airtable is a proprietary service, for the free-trial version, Airtable does not limit the number of bases users can create. Each work base is able to hold up to 1,200 items, with 2GB space for attachment. I think such capacity on a free-trial version is big enough for small organizations and individual users’ daily data management. The free version also enables 2-week’s revision history tracking. 

If you want to manage more than 1,200 records in one base, the monthly cost is US10/month (pay annually), allowing users to manage up to 5,000 records per base and 6-month history tracking. Under his paid plan, the space for attachment in each base will be increased to 5GB. See [princing plans](https://github.com/jyw321/Airtable_Exercise/blob/master/Image_2.png)

**Versatility of fields**: Each cell can accommodate contents of various types, including texts, numbers, option tabs, time duration, currency, percentage, images, and more. Here, for instance, the time duration function is tremendously practical for AV collections. By choosing the time duration format of your own (e.g. hh:mm:ss or hh:mm), Airtable could help you calculate the total duration time. This is a function that Excel or Google Form lacks. 

**Flexible view options**: Users can choose to view certain number of columns at one time, by hiding other columns that make the long sheet. Users can also share the “view” of only certain number of columns to other people, no need to re-create a new table. 

Data could be shown in Grid View, Form View or Gallery View, serving different kinds of data styles. This function is very useful for office collaboration.

**Relational function**: Tables in one base could be linked with each other. It means that one same item appear in different tables could be easily associated, freeing users from jumping from one table to another. I find this is greatly useful for event management, as different elements in one event plan could be linked to their specific record (will demonstrate more later). 

**Collaboration**: Like Google Form, Airtable allows multiple editors in the same base. 

**Product support team and active community**: Airtable prepares a comprehensive support page for users to seek [trouble solutions](https://support.airtable.com/hc/en-us). And an active [user community](https://community.airtable.com)is out there.

**API**: Airtable provides [API](https://airtable.com/api) for users in need. JSON is the language of encoding. Standard HTTP codes are used to signal operational outputs. This is a function useful to small scale organizations especially memory institutions. From time to time, organizations may receive requests from users who hope to fetch the data in batch for research purpose.

**Data security**: Transmission of information between users’ devices and Airtable servers is protected using 256-bit TLS encryption. At rest, Airtable encrypts data using AES-256. Airtable servers are located in the US, in data centers that are SOC 1, SOC 2 and ISO 27001 certified. Airtable’s data centers have round-the-clock security, automatic fire detection and suppression, fully redundant power systems, and strict controls for physical access. Airtable regularly installs security updates and patches to keep servers up to date. 

Airtable utilizes industry-leading Amazon Web Services (AWS) hosting infrastructure. Backups are replicated across multiple availability zones for data durability. Airtable is fully compliant with the General Data Protection Regulation ("GDPR"). Airtable believes that “your data is your data”, and they have strived hard to protect them from being exposed and destroyed . That being said, data security is a key issue that organizations need to take into serious account when they apply Airtable to manage their data. See [Data Security](https://airtable.com/security)

### Now let's take a look at some [basic concepts](https://github.com/jyw321/Airtable_Exercise/blob/master/Some%20Basic%20Concepts%20of%20Airtable.md) that would help you get familiarized with Airtable.
