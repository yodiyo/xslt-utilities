# Utilities used within XSLT

We created these utility templates to make developing XSLT templates more efficient and DRY

* Convert from lower to upper case and vice versa
* Remove non-alpha-numeric characters from string
* Replace string characters
* Remove "/version/" from path to file
* Return items as list with default comma separator
* Remove non-alphanumeric chars and replace spaces with _ in strings intended for use in URLs
* Create path to document removing version and adding forward slash separators
* Calculate date - receives dd.mm.yyyy and returns yyyymmdd
* Format date - expects dd.mm.yyyy hh.mm $date (time optional) and returns in UK or US (depending on environment) format
* Localisation for name or description - outputs English or translated version of 'name' 'description' node 
* Check elibility of asset or content, eg draft or approved status
* Use short name instead of full name if available
* Convert grades to numbers
* Create edit path based on store (asset or content type)
* Add "Read more" link to articles with links
* Convert video duration to hours, minutes, seconds

