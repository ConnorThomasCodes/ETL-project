# ETL-project

In this repository we access two csv files, fake_data_address.csv and fake_data_dob.csv (fake_data_address.csv was too big for standard upload into github), and create a merged dataframe on the full name of members from each file. We need to do some extra string manipulation using regex to process the names and addresses listed.

After creating and cleaning our merged dataframe, we are able to create an age column by subtracting curent date minus date of birth and converting the result from days to years. We can then filter our age column for only include people between 40 and 60, and then use formatted prints to output their names and addresses as desired.
