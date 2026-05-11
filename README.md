# ApplicantParserPDF

Note: After you initially go through steps 1-6 for the first time, there afterwards, simply open the file and proceed to step 7 on using the code. If you already have Python and VS Code installed, ensure that all necessary libraries are installed as per step 6.  

Step 1: Install Python 

Go to the Microsoft Store, and search “Python”.  

Download the latest version for your system (Windows/Mac). 

Run the installer and check the box that says, “Add Python to PATH”. 

Click Install Now.  

Step 2: Install Visual Studio Code (VS Code) 

Go to the Microsoft Store, or VS Code website.  

Download and install it for your system.  

Open VS Code after installing.  

Step 3: Install Python Extension in VS Code 

In VS Code, go to the extensions tab (left sidebar or press Ctrl+Shift+X).  

Search for “Python”.  

Click Install on the one published by Microsoft.  

Step 4: Open the Shared Code File in VS Code 

In VS Code, go to File -> Open Folder.  

Navigate to the folder where you would like to place the code file and click select folder. 

In VS Code, go to File -> New File, type “Python”, and click the Python File option.  

This should open a new Python file.  

Now open the provided .txt file for the parser. Copy and paste all the code into your new Python File.  

Perform Ctrl+S to save the file. Save this file in the folder you opened previously. You should now see the .py file in the folder sidebar on the left.  

Ensure that autosave is enabled by going to File -> Autosave.  

Step 5: Open a Command Terminal in VS Code 

Go to Terminal -> New Terminal. 

This will open a terminal window at the bottom of VS Code.  

Step 6: Install Required Python Packages 

Type in the terminal: pip install pymupdf pandas phonenumbers numpy opencv-python openpyxl and then click enter.  

This will install all the libraries used in the code. It may take a few minutes to install all libraries. After initial installation, you do not need to install them again.  

Step 7: Preparing the Files 

From the job application portal, download the applicant reports for all applicants.  

Note: If an applicant submits their resume or cover letter in .docx file type, when downloading the applicant reports, these two files will also be downloaded.  

Place all applicant reports in a folder of your choice (desktop or OneDrive).  

Note: You may choose to also put the .docx resume and cover letter files in this folder. This will not impact the code and allow you to easily access them.  

Download the “SelectionMatrix” Excel file and place it in the same folder with the applicant reports.  

Use “saveas” to convert the file format from “.xls” to “.xlsx”. 

You may format the cells before running the code, or after. The code will maintain the destination formatting.  

Step 8: Modifying the Code 

At the top of the code, above “Function Code”, find folder_path and excel_file_path.  

After the “r” in folder_path = r, copy and paste the path to the folder that contains the applicant reports.  

After the “r” in excel_file_path = r, copy and paste the path to the “SelectionMatrix” Excel file.  

Ensure that there is a single set of double quotation marks surrounding the file path, after the “r”.  

Step 9: Running the Code 

Ensure that all applicant reports are in the correct folder, and that the path has been added correctly in step 8.  

Ensure that the “SelectionMatrix” Excel file is in the same folder, and that the path has been added correctly in step 8.  

Ensure that the “SelectionMatrix” Excel file is closed; if it is open, the code will error out and will not run.  

Run the python file by clicking the run icon in the top right.  

Alternatively, in the terminal, type: python [Name of file].py and click enter. 

To open the terminal, go to View->Terminal.  

The code will take approximately 1.24 seconds per applicant report. Hence, depending on how many applicants reports you have, wait for 1.24*number of reports seconds.  

As the code is running, the terminal will look like this:  

 

Upon completion, the terminal will display a df (table) of values. This means the code has been executed.  

Now that the code has been executed, you can open the “SelectionMatrix” Excel file, and all your data has been loaded and is ready to process.  
