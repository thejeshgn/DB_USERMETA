# DB_USERMETA
The table name would be DB_USERMETA. Its a key, value table.
- key   - TEXT (ASCII)
- value - TEXT (UTF-8)

# Conventions for using key
- . is used as the operator to seaparate the concerms
- col is for column
- tbl for table
- v for version
- ASCII encoding

# Conventions for using value
- for version user sematic versioning 
- UTF-8 encoding
- dates will be yyyymmdd

#basic is the primary concern. These keys are predifined
- basic.title
- basic.description
- basic.copyright
- basic.copyright.url
- basic.author
- basic.author.url
- basic.author.email
- basic.source
- basic.source.url
- basic.source.email
- basic.current.release.version
- basic.current.release.date


#release is used for release, description
- release.{version}.title
- release.{version}.description
- release.{version}.date
- release.{version}.author
- release.{version}.author.url
- release.{version}.author.email

#tbl is used for defining table and col for the column
- tbl.{actual_table_name}.title
- tbl.{actual_table_name}.description
- tbl.{actual_table_name}.col.{actual_column_name}.title
- tbl.{actual_table_name}.col.{actual_column_name}.description
- tbl.{actual_table_name}.col.{actual_column_name}.format
- tbl.{actual_table_name}.col.{actual_column_name}.unit




