[Folder] Field_Sheets (Contains all the sheets we have from the field data)
->BDF_2019_1 (this is a raw sheet from their first trip)
->BDF_2019_1_alt (This is one of our augmented sheets where we derived the missing blocked entries, might prove useful)
->BDF_2019_3 (Another raw sheet with blocked entries from second or 3rd trip... its unclear)
->BDF_2019_3_alt (Another augmented sheet where we parsed out entries, but may have different data)
*Each of these have spanish column headings
[Folder] Museum_Sheets (Contains Museum Data)
->Museum_Peru_2020 (Contains entries for ALL 2020 entries of museum data, includes catalog number for SI)
*There is 1 sheet taken in 2019 that is not included here, there are no associated image numbers, just the camera numbers which we never were able to connect (this was taken before I started). I do have these data and might have a way for use to make the inference, but we would need to wrangle the rest of the data.

[Stand Alone File] Fish_label_list (This is the master list, derived from the images I used, of all the images used for training the model by genus and image name)
Use this to compare other data to in order to ensure we've got everything accounted for. 

We'd like to have a final document that has the following-

Image_name, Genus, species, Data_source (Field or Museum), Locality (Country), Si_ID (if it has one). 

Maybe a separate csv with the image_ids/name of entries with missing data from the Fish_label_list master file.
