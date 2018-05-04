# PhilipsHueOnPowerCut
Simple bit of python code to make sure all Phillips Hue lights return to previous state after a power cut instead of going to 100%

If you stay in India, or any other place with frequent power cuts, chances are that your Phillips Hue Lights are a bit of a pain when the power gets cut and the generator kicks in in the middle of the night and all of them shoot up to 100%. 
This little bit of code restores each light to it's previous state after a power cut. 

Follow the Phillips Guide to first setting up a username to connect to the Hue Bridge. You can find it at https://developers.meethue.com/documentation/getting-started

Then simply change the IP address, username and the dictionary for your lights, and you're good to go! 
