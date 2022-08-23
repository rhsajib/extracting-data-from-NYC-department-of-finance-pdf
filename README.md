## scraping-data-from-pdf

#### Project description

This project contains an Excel spreadsheet with links to website in the following form:

https://a836-edms.nyc.gov/dctm-rest/repositories/dofedmspts/StatementSearch?bbl=4082890044&stmtDate=20210227&stmtType=SOA
https://a836-edms.nyc.gov/dctm-rest/repositories/dofedmspts/StatementSearch?bbl=4023080027&stmtDate=20210227&stmtType=SOA
https://a836-edms.nyc.gov/dctm-rest/repositories/dofedmspts/StatementSearch?bbl=3027491001&stmtDate=20210227&stmtType=SOA
https://a836-edms.nyc.gov/dctm-rest/repositories/dofedmspts/StatementSearch?bbl=4101220018&stmtDate=20210227&stmtType=SOA

Each link is to take to a pdf file. For example, the first link will take to a web page with the following, where required seven fields are labeled with red numbers:

![Screen Shot 2022-08-23 at 8 28 32 PM](https://user-images.githubusercontent.com/111883695/186184963-f4313c85-7cd5-4303-9a9a-6c860271b9a3.png)

Data were taken from fields 1-7 and placed into a spreadsheet like this:

![Screen Shot 2022-08-23 at 8 36 20 PM](https://user-images.githubusercontent.com/111883695/186186542-df32aec3-6571-4fd9-9036-a290e887ef31.png)
This process was iterated for each of the 12 links. It can be done for thousands of links.

#### Target
Autoutomating this process to extract the data from each link and populate spreadsheet with those 7 fields.
