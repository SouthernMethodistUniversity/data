[<<< Previous](https://github.com/SouthernMethodistUniversity/data) | [Next >>>](dhdata.md)  

# What is data ? 
* What are the stages of data ?
* We begin without data. Then it is *observed*, or *made*, or *imagined*, or *generated.* After that, it goes through further transformations.

## Raw data 
* Raw data is yet to be processed, meaning it has yet to be manipulated by a human or computer. Received or collected data could be in any number of formats, locations, etc.. It could be in any of the forms listed [further down](https://github.com/SouthernMethodistUniversity/data/blob/master/sections/types.md#forms-of-data).

* But "raw data" is a relative term, inasmuch as when one person finishes processing data and presents it as a finished product, another person may take that product and work on it further, and for them that data is "raw data". 

* For example, is "big data" "raw data"? How do we understand data that we have "scraped"?

## Processed/transformed

* Processing data puts it into a state more readily available for analysis, and makes the data legible. For instance it could be rendered as **structured data**. This can also take many forms, e.g., a table. 

* Here are a few you're likely to come across, all representing the same data:

### XML

```
<Cats> 
    <Cat> 
        <firstName>Smally</firstName> <lastName>McTiny</lastName> 
    </Cat> 
    <Cat> 
        <firstName>Kitty</firstName> <lastName>Kitty</lastName> 
    </Cat> 
    <Cat> 
        <firstName>Foots</firstName> <lastName>Smith</lastName> 
    </Cat> 
    <Cat> 
        <firstName>Tiger</firstName> <lastName>Jaws</lastName> 
    </Cat> 
</Cats> 
```

### JSON

```
{"Cats":[ 
    { "firstName":"Smally", "lastName":"McTiny" }, 
    { "firstName":"Kitty", "lastName":"Kitty" }, 
    { "firstName":"Foots", "lastName":"Smith" }, 
    { "firstName":"Tiger", "lastName":"Jaws" } 
]} 
```

### CSV
```
First Name,Last Name/n
Smally,McTiny/n
Kitty,Kitty/n
Foots,Smith/n
Tiger,Jaws/n
```

### The importance of using open data formats
A small detour to discuss (the ethics of?) data formats. For accessibility, future-proofing, and preservation, keep your data in open, sustainable formats. A demonstration:

1. Click on [this link,](https://github.com/SouthernMethodistUniversity/data/blob/master/sections/cats.zip) and then click on the Download option on the right hand side of the page. This will download a .Zip file, which contains 2 files named cats. 
2. Open cats.csv file in a text editor, and then in an app like Excel. This is a CSV, an open, text-only, file format.
3. Now try to do the same with cats.xlsx. This is a proprietary format! 

Sustainable formats are generally unencrypted, uncompressed, and follow an open standard. A small list:

* ASCII

* PDF 

* .csv

* FLAC

* TIFF

* JPEG2000

* MPEG-4

* XML

* RDF

* .txt

* .r

How do you decide the formats to store your data when you transition from 'raw' to 'processed/transformed' data? What are some of your considerations?

## Tidy data
There are guidelines to the processing of data, sometimes referred to as **Tidy Data**.<sup>1</sup> One manifestation of these rules:
1. Each variable is in a column.
2. Each observation is a row.
3. Each value is a cell.

Look back at our example of cats to see how they may or may not follow those guidelines. **Important note**: Some data formats allow for more than one dimension of data! How might that complicate the concept of **Tidy Data**?

```
{"Cats":[
    {"Calico":[
    { "firstName":"Smally", "lastName":"McTiny" },
    { "firstName":"Kitty", "lastName":"Kitty" }],
    "Tortoiseshell":[
    { "firstName":"Foots", "lastName":"Smith" }, 
    { "firstName":"Tiger", "lastName":"Jaws" }]}]}
```

 <sup>1</sup>Wickham, Hadley. "Tidy Data". Journal of Statistical Software.


## :white_check_mark: Discussion: Forms of data :white_check_mark:
These are some (most!) of the shapes your research data might transform into.
* What are some forms of data you use in your work?
* What about forms of data that you produce as your output?
* Perhaps there are some forms that are typical of your field? 
* Where do you usually get your data from?

## Forms of data

There are many ways to represent data, just as there are many sources of data. After processing our data, we turn it into a number of products. For example:

* Non-digital text (lab books, field notebooks)

* Digital texts or digital copies of text

* Spreadsheets

* Audio

* Video

* Computer Aided Design/CAD

* Statistical analysis (SPSS, SAS)

* Databases

* Geographic Information Systems (GIS) and spatial data

* Digital copies of images

* Web files

* Scientific sample collections

* Matlab files & 3D Models

* Metadata & Paradata

* Data visualizations

* Computer code

* Standard operating procedures and protocols

* Protein or genetic sequences

* Artistic products

* Curriculum materials

* Collection of digital objects acquired and generated during research


[<<< Previous](https://github.com/SouthernMethodistUniversity/data) | [Next >>>](dhdata.md)  

-----

[Return to introduction](https://github.com/SouthernMethodistUniversity/data)

List of forms adapted from: [Georgia Tech](https://libguides.gatech.edu/)
<!-- now unpublished guide (http://libguides.gatech.edu/content.php?pid=123776&sid=3067221)!t --> 
