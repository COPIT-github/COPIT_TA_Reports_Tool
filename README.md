# TA Reports Generator
#### Author : [Suryateja Kurella](https://www.github.com/suryaKurella) 

This is the code to generate TA reports for COPIT. 

This project is developed with Node JS and Swagger API docs.
Node JS uses Javascript and Swagger requires YAML configurations.

## Installation


```bash
npm install
```

## Usage

1. Currently this code isn't hosted anywhere and could be run from local.

2. Please upload only the cleaned excel file. 
3. 
   cleaned = leave no blank rows.
   
   The following column data should never be blank for any record, if one or more of the below fields are blank, then one or more of the 4 reports will not be generated and program terminates.
   * Coordinator Name
   * Course Name
   * Total Course Hours
   * Name
   * Hours of Work
   * Work Performed
   * Hours of Work

4. Git clone this code and run ```npm install``` in the code terminal.

5. Run the main.js file so as to start the server which is made by default:5000, please change accordingly.
6. The app can be opened by the following route http://localhost:5000/api-docs.
7. The default page looks as follows
 
![image](https://user-images.githubusercontent.com/34373886/160030406-2f75a42d-f7dc-4294-ba08-2b24e5831d45.png)

8. Click on "POST" to show the options for file upload, Term and Year.

![image](https://user-images.githubusercontent.com/34373886/160030511-46756938-0815-428f-81a4-7b113cc6e0fb.png)

9. Click on ```Try it out``` to enable the buttons in step 6.
10. Upload the TA file, select the Term from the dropdown and type in the Year(which is 2021 by default). All these fields are mandatory.

![image](https://user-images.githubusercontent.com/34373886/160030762-0e5be6be-8a91-42fd-808e-b2b8bb93c3ef.png)

11. Click on  Execute button, wait till the "Loading" option disappers, the 4 TA report files get generated in the outputs folder.

![image](https://user-images.githubusercontent.com/34373886/160031013-b30a5bd5-a9f8-467c-8f39-1f8a8717ee26.png)

12. Please see the API docs UI, make sure that we get ```200 ok``` server status which indicates that our file generation operation is succesful.





## Debug

1. The code is easy to understand and could be debugged with appropriate console log statements.
2. Console log indexes wherever necessary to find the row number


## Could be improved further

1. Can migrate the entire project with ```React``` as frontend and ```Node JS``` backend.

2. Refactor the entire code to the latest ES versionor or refactor the existing redundant code.
 
3. Host the entire site in cloud either in heroku or netflify for free.

4. Make necessary code changes to download the output files, for now since it runs locally, the output files are stored in the local project directory. 

5. Make CI possible.




