# readFormattedExcel
## Java program to read a formatted excel file
The goal of this project is to parse the excel file and return the a JSON file and a CSV file with all the data parse. following the criteria above:

1. Maven Project
2. Should have unit tests
3. Written in a modular way and in a general porpuse way also, be able to read some variances of the same type of file (variances in the headers or titles)
4. Java 8 compatible


## About the excel file
1. This excel file is a part of a vast data set storage in excel sreadsheets, indicating four types of data; String, Date, Float and Integer
2. The headers must be preserved no matter what in the follow JSON String;

{
    "orderName":"",
    "modelNumber":"",
    "order":[
        {
            "orderNumber":"0001",
            "parameter":[
              {
                "paramterName":"Header1 : Header2 : Header3 : ColumnName",
                "value":"",
                "datType":"",
              }
            ],
            "block":"",
            "subBlock":""
        }
    ]
}
The order number field should be a 4 char String, and the parameterName should be delimited by ":" for every headers if is any, if not is just the name.

3. The Blocks is grouping indicators in the middle of the data rows, is just for visualization porpuses, nevertheless needs to be part of the data. 
