# can_ratings

src\python\notebooks -- test notebooks
-- sdat-etl.ipynb - builds sdat from MD web urls, joins geo and assessments
-- rental_licenses-etl.ipynb - joins cleand rental csv to prior can research
-- violations-etl.ipynb - parses comcate report, explodes violation code column, merges contacts
-- base_scoring.ipynb - merges owners across tax id, scores by assessment and size of holdings

The code violation data was intended for 2 uses, additional score attributes and additional ownershi clustering.  Since discovering the Minneapolis tiering system, this will be diverted to a separate report joining rental_licenses-etl with the exploded and summarized violation counts.

