# HCONPICodes
This repository will show how to acquire the propietary HCO codes and NPI numbers from Health Care Options.


Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. You would have to update to the latest version of python. Once it is installed, you would have to download the scrapy module. Use your terminal or your preferred IDE to download the scrapy module. 

Prerequisites
Laterst version of Python and Scrapy module. 

In command module/terminal run install scrapy. Once scrapy has begun its project, you need to input into the terminal scrapy startproject "project name." Once scrapy has downloaded all the files you can create a new python file within the "spiders" folder. 

Copy paste the python code into the first file and then locate the items.py files and copy paste all the information there. 

Anytime you wish to run the spider you need to input scrapy crawl "spider name". If you wish to output the information to a specific file such as a .csv/.json file, then in the terminal after you enter scrapy crawl "spider name", you will have to input -o file name.csv. 

Example: Terminal input would say
scrapy crawl hco -o losangelepcp.csv

That line would output the pcp info to a csv file. 

The code specifies where you would have to change the county number. 

The output would be specific to that county. All the files should then be combined into a one large file either through MS Access or Excel. 

Authors
Julio Rosales
