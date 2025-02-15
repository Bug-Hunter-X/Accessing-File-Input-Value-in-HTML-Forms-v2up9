# Accessing File Input Value in HTML Forms
This repository demonstrates a common error and its solution when working with file input elements in HTML forms.  The error arises from attempting to directly access the value of a file input using JavaScript. Due to browser security restrictions, simply accessing the `value` property will not provide the file's content but rather its path.  The solution presented shows how to correctly handle file uploads using JavaScript to access the actual file data.

## Error Description
The provided `bug.html` file contains a form with a file input.  The JavaScript code attempts to access and log the file's value. The output will not be the file content but rather a file path, which is not usually what is desired.

## Solution
The `solution.html` file demonstrates the correct approach using the `FileReader` API to access the file content. This allows for proper processing and handling of the selected file data.