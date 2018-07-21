# Get-DraftKings-Salary-Data

This repo is a Notebook tutorial of how to use the [mysportsfeeds.com API](https://www.mysportsfeeds.com/data-feeds/).

The tutorial is an exploration of the API, where I walk through:

1. writing Python functions to automate GET requests to the API
2. parse the JSON response into a list of dictionaries, which is a preferred format to
3. convert Python objects into a `Pandas` Dataframe.
4. Clean the dataframe, such as converting ISO 8601 formatted date strings into date objects.

The personal benefit of this exploratory work for me, is so that I can ultimately
take this learning and encapsulate the knowledge into a .py program that could be
automated, shared for other projects. 
