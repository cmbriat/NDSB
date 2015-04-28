This is the code to upload data into R. Everything should be called from the "get_data" file, except "get_test" and files that modify "Data".

The "remove_X" files should be used BEFORE we use variable selection or creating CV folds because they modify "Data".
  source(getData.path)
  source(removeWorst.path)
  source(getValidationSets.path)
