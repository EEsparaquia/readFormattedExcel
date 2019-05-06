# readFormattedExcel
## Java program to read a formatted excel file
The goal of this project is to parse the excel file and return the a JSON file and a CSV file with all the data parse. following the criteria above:

1. Maven Project
2. Should have unit tests
3. Writen in a modular way
4. Java 8 compatible
5. Writen in a general porpuse way, be able to read some variances of the same type of file (variances in the headers or titles)


## About the excel file
1. This excel file is a part of a vast data set storage in excel sreed sheets, indicating four types of data; String, Date, Float and Integer
2. The headers must be preserved no matter what in the follow whay: Header1,Header2,Header3,Header4,ColumnName,Data,Block1,Block2
3. The Blocks is agrouping indicator in the middle of the data rows, is just for visualization porpuses, nevertheless needs to be part of the data. 
