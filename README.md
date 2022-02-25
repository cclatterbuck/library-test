# library-test

This is a project that automates the processing of library records with errors.

It is designed for the average person's knowledge of Windows, but no or very
little knowledge of R. These instructions are tailored to meet this knowledge.

If you are seeing this on Github, you can:

1. Hit the green code button and select "Download ZIP" to download the file
system setup as well as the code; OR:
2. For those with more R/Git knowledge, clone the repo into your local system &
follow your typical R setup.

Assuming you chose (1) above, unzip the file and put it where you would like to 
access it in your local system. It should include all of the file folders needed
to run the code correctly. 

## Weekly workflow

1. Each week when you get new files to compile, create a new file folder in the 
rawdata folder titled with the numeric year, month, and day (e.g., 20220218 for
18 February 2022) and place the new files in that folder.

2. Open library-test.Rproj, which will open RStudio.

3. In the Files pane, navigate to LoadRecords.Rmd and open it. If you have not
read through LoadRecords.Rmd before, do so now.

4. Replace the name of the file folder in steps 2 & 5 of LoadRecords with the
file folder name you created above. 

5. Run each code block using the green arrow. Remember, you may need to run
each individual line in step 3 of LoadRecords. 

6. Look in the outputs folder to ensure the saved spreadsheets look correct.

7. Close the .Rproj without saving any files within RStudio -- this ensures no
potential errors are carried over to the next time you use LoadRecords.
