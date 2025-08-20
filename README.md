# Excel-data-cleaning-2



## Changing the data type of the Date field
![img alt](https://github.com/nsankareswari-70/Excel-data-cleaning-2/blob/14ca904d2f385492a02332e8c1fbe12ca57c82c0/ex151.png)


## Removing the Blank rows
![img alt](https://github.com/nsankareswari-70/Excel-data-cleaning-2/blob/eff6066bcd499b9faebcc3108f7cf1725efa14af/ex150.png)
Use the find and select button -> select Go To special - click Blank
All the blank rows are selected. Now go the Delete button on the menu. Select Delete sheet rows
Now all the Blank rows are deleted.

## changing the value column to currency type
![img alt](https://github.com/nsankareswari-70/Excel-data-cleaning-2/blob/d8dae3822d1e268bfc6795568540c71c9586b17e/ex152.png)

## Remove unwanted spaces in the Department column
Use the trim() to remove unwanted spaces

## Use the Upper(), Lower() and proper() functions to format the text
![img alt](https://github.com/nsankareswari-70/Excel-data-cleaning-2/blob/f6ff4d496b758270528df9950b93ab08b3d8ddce/ex153.png)

## Converting the data to table
use ctrl + T to convert the data into table format

## create a pivot table
![img alt](https://github.com/nsankareswari-70/Excel-data-cleaning-2/blob/950af3c58de84cfd806ae62c9e1492497aa9e490/ex154.png)
## import the csv file to excel
Using Get Data feature in excel
## Find the location of the ; 
Use find() function to get the location of the ;
=FIND(";",[@Column2])

## len(),left(),right() 

=LEN([@Trim])

=LEFT([@Trim],[@[; location]]-1)

=RIGHT([@Trim],[@length]-[@[; location]])

![img alt](https://github.com/nsankareswari-70/Excel-data-cleaning-2/blob/dd93df21036b8e45b448ea26687f35bcde115654/ex155.png)

## Converting the text into number
- Text is always left aligned
  
- Numbers are always right aligned in a cell
  
 ![img alt](https://github.com/nsankareswari-70/Excel-data-cleaning-2/blob/b23b49bac2924800a0a4f0e129ba0cd9fcf6ec6b/ex156.png)

 ## Substitute()
 =SUBSTITUTE(E29,"Mktg","Marketing")

  ![img alt](https://github.com/nsankareswari-70/Excel-data-cleaning-2/blob/4eba150d592caa330f3363e3c81516f8f382d498/ex157.png)
  
## replace all the R & D with research and development
 ![img alt](https://github.com/nsankareswari-70/Excel-data-cleaning-2/blob/956e358d6a0fe5cebc99dc99de5060e4ee8c6cc5/ex158.png)

 
  ![img alt](https://github.com/nsankareswari-70/Excel-data-cleaning-2/blob/956e358d6a0fe5cebc99dc99de5060e4ee8c6cc5/ex159.png)


    ![img alt](https://github.com/nsankareswari-70/Excel-data-cleaning-2/blob/830364e4af8096dad6e3cdf245be935195156553/ex160.png)

