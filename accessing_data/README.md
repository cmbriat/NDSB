This is the code to upload data into R. For simplicity, all "get_X" files should be called from the "get_data" file, except "get_test".

The "remove_X" files should be called BEFORE we use variable selection or creating CV folds because they modify "Data".

Example:
```
source(getData.path)
source(removeWorst.path)
source(getValidationSets.path)
```
