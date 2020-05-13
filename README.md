# shell-data-processing

## The curl command  which is used to get the data:
- Command:  curl "url" 
 - Chose url of your specified choice.

 ## The curl command  which is used to get the data and output to a file.

 - Command: curl "url" -O data.txt

 ## The command used to find the most common words, sorted is 

 - Command: tr ' ' '\12' < data.txt | sort | uniq -c