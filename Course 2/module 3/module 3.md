## Spreadsheets and the data life cycle
To better understand the benefits of using spreadsheets in data analytics, let’s explore how they relate to each phase of the data life cycle: plan, capture, manage, analyze, archive, and destroy.

- **Plan** for the users who will work within a spreadsheet by developing organizational standards. This can mean formatting your cells, the headings you choose to highlight, the color scheme, and the way you order your data points. When you take the time to set these standards, you will improve communication, ensure consistency, and help people be more efficient with their time.

- **Capture** data by the source by connecting spreadsheets to other data sources, such as an online survey application or a database. This data will automatically be updated in the spreadsheet. That way, the information is always as current and accurate as possible.

- **Manage** different kinds of data with a spreadsheet. This can involve storing, organizing, filtering, and updating information. Spreadsheets also let you decide who can access the data, how the information is shared, and how to keep your data safe and secure. 

- **Analyze** data in a spreadsheet to help make better decisions. Some of the most common spreadsheet analysis tools include formulas to aggregate data or create reports, and pivot tables for clear, easy-to-understand visuals. 

- **Archive** any spreadsheet that you don’t use often, but might need to reference later with built-in tools. This is especially useful if you want to store historical data before it gets updated. 

- **Destroy** your spreadsheet when you are certain that you will never need it again, if you have better backup copies, or for legal or security reasons. Keep in mind, lots of businesses are required to follow certain rules or have measures in place to make sure data is destroyed properly.	

## More about spreadsheet errors and fixes

| Error | Description | Example |
| :-----| :------: | ----: |
| #DIV/0!|   A formula is trying to divide a value in a cell by 0 (or an empty cell with no value)   | =B2/B3, when the cell B3 contains the value 0  |
| #ERROR!|   (Google Sheets only)  Something can’t be interpreted as it has been input. This is also known as a parsing error.    | =COUNT(B1:D1 C1:C10) is invalid because the cell ranges aren't separated by a comma |
| #N/A   |  A formula can't find the data    | The cell being referenced can't be found  |
| #NAME? |  The name of a formula or function used isn't recognized  | The name of a function is misspelled  |
| #NUM! |  	The spreadsheet can't perform a formula calculation because a cell has an invalid numeric value   | =DATEDIF(A4, B4, "M") is unable to calculate the number of months between two dates because the date in cell A4 falls after the date in cell B4 |
| #REF! |  A formula is referencing a cell that isn't valid   | A cell used in a formula was in a column that was deleted |
| #VALUE! |  A general error indicating a problem with a formula or with referenced cells   | There could be problems with spaces or text, or with referenced cells in a formula; you may have additional work to find the source of the problem. |


## The importance of context

**Context** in data analytics is the condition and circumstances that surround and give meaning to the data. Context is important in data analytics because it helps make disorganized data accessible and understood. The fact is, data has little value if it is not paired with context. 

Context can turn raw data into meaningful information. It is very important for data analysts to contextualize their data. This means giving the data perspective by defining it. To do this, you need to identify:

- **Who**: The person or organization that created, collected, and/or funded the data collection

- **What**: The things in the world that data could have an impact on

- **Where**: The origin of the data

- **When**: The time when the data was created or collected

- **Why**: The motivation behind the creation or collection

- **How**: The method used to create or collect it