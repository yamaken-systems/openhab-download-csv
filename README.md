# openhab-download-csv
this is a static HTML file that downloads persistent data to CSV file.

1.deploy

put on the csv.html file under your [openhab/conf/html/] directory.


2.how to use

2-1. access to [your openhab url]/static/csv.html on your browser.

ex. if openhab url is [http://192.168.11.101:52080],

then go to [http://192.168.11.101:52080/static/csv.html]

2-2. input your openhab url on the site.

2-3. click the [get item name] button,
     then get item name via openhab api,
     and set item name to dropdownlist.
     
2-4. select the item name you want to csv file the dropdownlist,
     and click the [get persistence data] button.
     
2-5. if you want to specify a range by date,
     please input pickup period. 
