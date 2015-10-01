###### Data Representation and Querying - Exercise 2
# JavaScript Object Notation
In this exercise we will look at the syntax and use of JavaScript Object Notation (JSON).

## Exercises
Save each exercise as a separate source file.

1. Download the files in this repository and open them in Brackets. Open javascript.html in Firefox, and open the JavaScript console.

1. Copy and paste the output of [reddit.com/.json](http://www.reddit.com/.json) into JSONLint. Check that the JSON output from Reddit conforms to the JSON standard.

1. Find the car object in javascript.html. Add another property to the car object, called year and give it a value of 2007. Refresh javascript.html in your browser.

1. Create a variable called jsontext in the JavaScript code that is a string containing only a pair of curly braces, delimited by single quotes.

1. Create a variable called jsonobj, which is the return value of JSON.parse called with jsontext as an argument. Check the result.

1. In jsontext, write the JSON code for an object with a single name/value pair, where the name is "breed" and the value is "labrador". Again, check the result.

1. Change the property's name to "breeds", and change its value to an array containing three strings: "labrador", "collie" and "springer".

1. Go to [JSONLint](http://jsonlint.com/), and copy and paste the contents of jsontext into the test box. Click Validate.

1. Change the contents of jsontext to represent an object representing a person's contact details, such as the name, surname, home phone number, mobile phone number, work email address, personal email address, and their children's names. You can choose your own names and values for the properties.

1. Test to make sure your JSON code is valid, and that JSON.parse can understand it.

## Advanced exercises

1. Try to use JSON.parse on the converted bond.csv file from the Advanced Exercises in [this](https://github.com/data-representation/json-introduction) repository.

1. Use JSON.parse on the JSON code returned from reddit.com/r/funny in the file json.html in that repository.

## Note

- JSON.parse on Mozzila's Developer Network: [JSON.parse()](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/JSON/parse#Syntax)

- JSON.stringify on Mozzila's Developer Network: [JSON.stringify()](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/JSON/stringify)
