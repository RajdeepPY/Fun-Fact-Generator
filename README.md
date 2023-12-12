# Fun-Fact-Generator
At first, run this command in your console pip install pywebio

Import all the required modules
Send GET requests with the requests.request() method, and use the json.loads() function to parse a valid JSON message and transform it to a Python Dictionary. Since the requests function will create a dictionary of items, and we only need text, so we will pass response.text inside the json module.
Now, because we need the text, i.e. Facts, we will pass the text within the data list and print the facts using the style function defined in the pywebio module. Because data is a dictionary of random jokes involving several useless items, we will just get the text section.
