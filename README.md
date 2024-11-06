# nosql-challenge
nosql-challenge
#### The nosql-challenge poses a hypothetical analysis of the data used by UK Food Standards Agency and their hygience to each establishment evualuated.
#### The use of Mongo DB was used in order to get the data from the json file in the resources folder located on the starter code zip. Though given a recent change in the local pc used to write the code the file path for the import on Mongo DB the output is not included at the time. Though with Mongo DB set up without issue the code runs without a problem.

#### Code: NoSQL_setup_starter
##### The addition of the final loop to check the coordinates and rating values was suggested by Xpert Learning Assistant
##### Also a correction in logic found on this code snipet was corrected with Xpert Learning Assistant "for field in fields_to_check:
######        try:
######            # Split the field to handle nested fields
######            keys = field.split('.')
######            value = document
######            for key in keys:
######                value = value[key]

#### Code: NoSQL_analysis_starter
##### Syntaxis errors found on the following code snipet were rectified with Xpert Learning Assistant " query = {'RatingValue': 5,
######    'geocode.latitude': {'$gte': latitude - degree_search, '$lte': latitude + degree_search},
######    'geocode.longitude': {'$gte': longitude - degree_search, '$lte': longitude + degree_search}
