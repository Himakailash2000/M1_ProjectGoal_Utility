# TEST PLAN

## High level test plan

|Test ID| Description| Input| Expected Output|
|:------|:-----------|:-----|:---------------|
|HL01|Add Book|Category,BookName,Author,Price|Category,BookName,Author,Price|
|HL02|Delete Book|Category, ID|Category,ID|
|HL03|Search Book|Category,ID|Category,ID|
|HL04|View Book|Category, ID|Category,ID|
|HL05|Issue Book|Category, ID|Category, ID|


## Low level test plan

|Test ID| Description| Input| Expected Output|
|:------|:-----------|:-----|:---------------|
|LL01|ADDIND DETAILS OF NEW BOOK|CATEGORY, BOOKNAME, AUTHOR, PRICE|Category,BookName,Author,Price|
|LL02|DELETING BOOK BY ID&CATEGORY|CATEGORY,ID|CATEGORY,ID|
|LL03|SEARCH FOR THE BOOK BY ENTERING CATEGORY,ID|CATEGORY,ID|CATEGORY,ID|
|LL04|ISSUING BOOK BASED ON ID|CATEGORY,ID|CATEGORY,ID|
|LL05|VIEW BOOK BY ENTERING CATEGORY,ID|CATEGORY,ID|CATEGORY,ID|