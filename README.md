# UrlHaus_CSV_Parser
This is a tool to extract Lines a from the Downloaded CSV file From URLHaus here 
https://urlhaus.abuse.ch/api/

You can see the Twitter thread for Screenshots.
https://twitter.com/Ledtech3/status/1296902393414725632

I use the top button under database dumps.

The Intended use for this tool is to narrow down the list from the data dump by various search strings.
The sample I got has 425,944 lines and there are various types of malware.

This is a "Dumb" filter so you can only search for 1 string at a time.

Say you want to list only the lines that have a tag of Emotet (The reson for building this)
We first Select the downloaded CSV file 
Then just enter the tag  emotet  and click the button.
It will return a list of only lines with emotet in it.

If you want to narrow it down further you can save that to a file then do a new search.
When you have it filtered down to where you want then you can choose what properties to filter out.
Note: if you try and search a new list without the origional 8 properties in it then it will throw an error.
      You might be able to recheck everything again and then filter by a new string because of the way it is written.


Note: the search is case sensative so just copy paste the search string from the data to be sure that is correct.


Other Ideas is to search by extension com,edu,ru etc.
Also say you may want to see just anything not HTTPS: so search for http:
Search by reporter.
Many more.

the password for the file is clean


