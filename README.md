# img-embed
Python tool that turns a html file + a collection of linked png files into a single self-contained html file.
## Usage
png-embed my_html_file.html
>> outputs my_html_file-images.html, a bigger HTML file that contains all the
>> (local) png files referenced in my_html_file.html. Note: this does NOT parse
>> html, therefore the search & replace method is extremely basic and not
>> intended to distinguish between real <img> tags and anything that might look
>> similar.
