# mini-course



# The data running in the Step 1


df; dataframe;  (23992,2)
headers; dict; 1
root_url; str;  1
years; list; 258

# Step 1

The code retrieves the URL address of http://caselaw.findlaw.com/court/us-supreme-court/years/ and downloads Supreme Court cases between 1716 and 2018. The code counts the number of cases and puts them in a table. The data is ready to be used for machine learning purposes.

# Step 2

The code uses the same URL as in Step 1 and downloads all the cases into full_project. Then, the final step is to put full_project in your local folder. The data is has been processed.

# Step 3

A stopword list is created and the program must now learn to remove the stopwords from the case load data that was processed in the previous step. The stopwords include state names, case names, common stopwords, people’s name, months. The last step is lemmatizing. The file "casetitles.csv" and "statenames.csv". I didn’t see the file "full_proj_preproc.pickle" was read to be processing.

# Step 4

Here, the code uses a machine learning algorithm to output a topic model. Three different kinds of models are used: LDA (with TF); NMF (with TFIDF); LSA - AKA TruncatedSVD (with TF and TFIDF).


# Step 5

This step arranges the data for visualization.
