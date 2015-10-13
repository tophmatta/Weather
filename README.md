# Weather

This app concatenates a NSURL with the city that the user inputs into the TextField to fetch a weather forecast. 
When the 'Go' button is pressed, a NSURL session is created and weather information nested within
the HTML of the webpage is stored and updated to the view via an IBOutlet.

Skills/objects used:
- Async programming
- NSString to call 'componentsSeparatedByString' method
- 'touchesBegan' to dismiss keyboard when done typing
