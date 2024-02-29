# Random-File-Generator

Random File Generator ( Random txt File Generator ) 

## The "Random File Generator" is a simple web application that generates a random 1 MB file and allows the user to download it. 

## Explanation of the code:

1. The HTML file includes a title, some basic styling using CSS, a heading for the application, and a button with the text "Generate 1 MB File".

2. The JavaScript code is responsible for generating the random content and triggering the download when the button is clicked.

3. When the button is clicked, an event listener is triggered that generates random characters from the specified character set (uppercase letters, lowercase letters, and numbers) until the content length reaches 1 MB.

4. The generated content is then converted into a Blob object with the MIME type 'text/plain'.

5. A temporary link element is created with the URL of the Blob object and a specified download filename.

6. Finally, the download is triggered by simulating a click on the link element.

Overall, this code creates a simple web application that allows users to generate and download a random 1 MB file with the click of a button.

## Link of Random-File-Generator Website

https://ivucb4t.github.io/Random-File-Generator/
