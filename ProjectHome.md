Autocomplete, when added to an input field, enables users to quickly find and select from a pre-populated list of values as they type, leveraging searching and filtering.

By giving an Autocomplete field focus or entering something into it, the plugin starts searching for entries that match and displays a list of values to choose from. By entering more characters, the user can filter down the list to better matches.

This can be used to enter previous selected values, for example you could use Autocomplete for entering tags, to complete an address, you could enter a city name and get the zip code, or maybe enter email addresses from an address book.

purpose :

- You can pull data in from a local and/or a remote source: Local is good for small data sets (like an address book with 50 entries), remote is necessary for big data sets, like a database with hundreds or millions of entries to select from.

- Autocomplete can be customized to work with various template, by just specifying the source template option

- the callback, provides the most flexibility, and can be used to connect any data source to Autocomplete. The callback gets two arguments:

- Pagination support, it use for any large data set and with pagination you can speed up your work :)

- Simple configuration and using, AJAX and local data models, Scrollable suggests list, Multiple suggests support, Tested on all popular browsers