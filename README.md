This is a .hmtl file that runs on any web browser with a Javascript code that 
1) Reads a user input .srt subtitle file
2) Parses it into an array separating timings and text
3) Feeds the text line by line to a Google API translator function
4) Converts the translated result back to plain text with the original timings and save to a file

USAGE: 
1) Assuming you already have a Google account, navigate to https://console.cloud.google.com/ and create a New Project. Then generate your API key.
2) Replace your generated API Key in the line: const apiKey = 'Replace with your actual API key'; 
