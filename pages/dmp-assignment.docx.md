**Project Title – Project Subtitle**

**Data Management Plan**

**Project Description**

*Describe the project, its topic, and its technical requirements. This should be a short summary of the technical aspects of the project.*

Our project highlights many different sculptures and antiques that depict the Gorgonian Medusa historically from Greek Mythology. This includes many different eras, from 600 BCE, to the 20th Century. The idea of this topic is to allow people to see how Medusa is depicted by people through their work, whether it may be evil, or beautiful. This collection is made and hosted using Github, which is a platform that allows people to create, collect, and share data. Mainly using CollectionBuilder, a template through Github that uses collected metadata to build a site that can be customized to display our data.

**Roles and Responsibilities**

*List project partners and explain how data management responsibilities were coordinated across partners.*

.

**Anticipated Data**

*Briefly describe what your data is and how it was collected. This should include your images, metadata, and repository contents.*

Our data is made up of images of sculptures that depict the beheading of Medusa. These images were mainly found via online Museum websites and public domain archives. The metadata was also obtained from these websites. Our metadata fields include regular elements, such as the  date, author, and title, as well as two custom metadata fields categorizing the objects by “Materials” and “Sculpture Type”. The repository contains roughly 13 megabytes of data in total, which can mostly be attributed to the images and pre-written code by GitHub. Such data was first recorded in Google Sheets and then exported for use on GitHub.

*In the table below, group your items by file type, then sum up the \# of items, the size in MB, and data sources for each grouping.*

| Item Description | File Type | Size (in MB) | \# of Items | License(s) | Sources |
| :---- | :---- | :---- | :---- | :---- | :---- |
| **Images** | **.jpg / .jpeg** | **8.04** | **27** | **Public Domain, Unlimited Re-Use, Attribution-Non-Commercial-ShareAlike 4.0 International, Copyrighted (Educational   Use Permitted), Available for educational use, Attribution 4.0 International, Attribution-ShareAlike 3.0 Imported** | **Met Museum, Minneapolis Institute of Art, Picryl, Digital Public Library of America, The Cleveland Museum of Art,  Europeana, Art Institute of Chicago. Getty, Yale University Art Gallery, JSTOR (Journal Storage), Statens Historiska Museer, Newfields** |

*State what specialized tools, software, and/or code are needed to access or manipulate the data and how they can be accessed. What does your CollectionBuilder site need to run?*

**Documentation and Metadata**

This data is easily accessible on our GitHub website for public consumption and reuse. Some metadata can be found on the “Data” tab of our website, whereas both images and all of the metadata can be found in the “Browse” section. Such data can be downloaded quickly via the use of our Data Dictionary in either Excel or CSV format.

**Storage and Backup**

Due to having extensive amounts of images and data, we have to store it in a place that is accessible and secure. Our metadata is collected and put into google sheets, while files like the csv./metadata and images are stored in a google drive. The repository is stored in Github. Everything that includes the actual data is stored and has backups, along with links to where the images are sourced in case of dire emergency. 

**Data Sharing**

Our data was found using many different galleries, archives, and museums. Since they were found in those, they can be found through things like the *Smithsonian*, but also our CollectionBuilder. Since all the images we display in our CollectionBuilder are found through the Public Domain, they can be easily reused and downloaded following links on our page that take them to the original website. There it can be downloaded.

**Period of Data Retention**

Each component of data in this project will continue to exist as long as Google Drive and Github exist. Since these components are stored in a public repository and a storage system using cloud, there will most likely not be any intentions of removing them. 

**Licensing and Ethical Issues**

All items used in our collection are a part of the Public Domain and can be downloaded and shared freely. Though, if there are any concerns, we have links for each item directed to a Creative Commons / Copyright website explaining what law they fall under.

**Appendix: Data Dictionary**

* *Your data dictionary is a the key to your metadata.*  
* *You do not need to alter the standard definitions of fields required by CollectionBuilder, **but example values should come from your collection**..*

| field | definition | example |
| :---- | :---- | :---- |
| objectid | Noclamenture for each distinct object that  | medusa001 , medusa002 , etc. |
| filename | Naming scheme that distinguishes objects by the category of artwork or subject with its associated date of creation | medusa\_charm\_1870.jpg |
| title | The original title of the artwork bestowed to the object by its creator or its modern purveyor (Museums, owners of private collections, etc.) | Head of Medusa |
| creator | The creator of the object, represented by name, or expressed as “Unknown” if the creator’s identity has been lost to time | Antonio Canova |
| date | Date attributed to the artwork’s creation; some such dates are rough approximations due to the fact that  | 1806 |
| description | A short, detailed account of what the artwork depicts, clarifying the subject, method of creation, or materials | Cameo carving of Medusa’s decapitated head surrounded by the symbols of Mercury’s caduceus. |
| source | The public or private institution each object, represented by a link to the site that displays images and metadata of each object | [https://www.metmuseum.org/art/collection/search/204758](https://www.metmuseum.org/art/collection/search/204758) |
| format | The type of image format used for images of each object | image/jpg |
| language | The original language of the website that contains images and metadata of each object | eng |
| rights | The categorization of an object’s status pertaining to reuse | Public domain |
| rightsstatement | A link to a website that explains in which ways the object can be legally reused | [https://creativecommons.org/publicdomain/zero/1.0/](https://creativecommons.org/publicdomain/zero/1.0/) |
| materials | The materials used to create the object | Marble |
| subcategory | The artistic subcategory that the object belongs to based on the method and medium of creation | Metalwork |

