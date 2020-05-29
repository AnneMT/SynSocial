Generates Synthetic Social Media Messages using Synthetic Health Records as Input

This Python program generates social media messages in Twitter JSON format based upon SyntheaTM https://synthetichealth.github.io/synthea/ generated Electronic Healthcare Records (EHR). FHIR data in JSON format is input to SynSocial and a collection of Twitter messages (Tweets) is generated for each patient record.

Input data needs to be stored in the \data folder. Output data and statistics on the number of messages generated (Excel file) are written to the \output folder. The output statistics file (Excel file) is overwritten each time the program is run.
Generated social medial messages (Tweets) (in JSON format) are appended to the text files corresponding to the patient's name. SynSocial uses reference data (Excel files) stored in \ref-data folder. (Update the file paths as needed for your installation/use.)

Tweets are generated from the Twitter Estabishment Date (TED) to the date set for today (TODAY) variable constants. (These dates can be modified as needed for your use.) The number of messages generated can be limited to 10 (or other value) by removing the comment mark at line 763 if needed for testing.

Please contact Anne Tall for any questions or comments