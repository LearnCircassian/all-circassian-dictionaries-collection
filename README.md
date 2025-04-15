# All Circassian Dictionaries Collection

This repository contains a collection of Circassian dictionaries that have been gathered from various sources, processed, and organized in different formats for use on the [Learn Circassian](https://learncircassian.com) website.

## Folder Structure

### 1. `rawData`
This folder contains the original, untouched Circassian dictionaries as they were obtained.  
- Most of the data here is unstructured and unparsed.
- Some dictionaries were received in HTML format directly from their original sources, making them difficult to convert to JSON.
- No modifications have been made to the content in this folder.

### 2. `organizedData`
This folder includes dictionaries that have been partially processed and modified into a more workable state.
- The data has been cleaned up and made more consistent.
- HTML-based dictionaries from the `rawData` folder could not be fully converted to JSON.

### 3. `organizedDataInHTML`
This folder contains the finalized version of the dictionaries, fully converted into HTML format.
- These are the files currently used on the Learn Circassian website.
- Each file includes all necessary HTML layout and styling classes for seamless integration with the frontend.
- Because several dictionaries originally came in HTML and were hard to convert to structured formats like JSON, the decision was made to convert **all** dictionaries into a consistent HTML format instead.
- This approach allows the use of HTML rendering libraries on the website to faithfully preserve layout, spacing, and styling from the original sources.

## Contributing

If you're able to parse the HTML-formatted dictionaries into clean JSON structures, your help would be greatly appreciated!  
With properly structured JSON, we can move toward a fully JSON-based system, making the data easier to process, search, and work with across different platforms.
