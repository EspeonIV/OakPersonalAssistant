# OakPersonalAssistant

Oak
Readme
A Hampton University Voice Assistant



Coleman Scott, Brooke McAdoo, Nicoh Carter,

Eric Sturgill, Raymond Martin, Ernest Horton, Joel Magee

Table of Contents
** 3**
3
3
** 5**
How to Replicate
To replicate the project go to the Github for the Oak Personal Assistantand download the index.html which is the Hampton website and Oak_1_954fd7e2-56f6-485c-a274-4668b697479d_Bot_LEX_V1.zip which is the intents or current questions you can ask the bot. from the repository. With these a new lex project can be made.

Starting Lex

Go to the Amazon Lex Website at https://aws.amazon.com/lex/
You will need to log in with your Amazon account
Then create a bot by clicking "CREATE"
Create a custom bot
Follow the rest of the instructions
After the creation of the bot got to the editor tab and click "Create Intent"
Then select "Import Intent" and use the JSON file from the zip file downloaded off of Github.
Go to https://aws.amazon.com/blogs/machine-learning/deploy-a-web-ui-for-your-chatbot to put the bot onto the replica of the Hampton website.
The index.html will be used during this process.
How to Use
To view the current iteration of the Assistant online you can go to one of two places. Both places connect to the same AWS Lex powered backend and bank of information.

Focused Client

There is anassistant specific chat client that provides a focused UI for communicating with our AWS bot. This is a location that is good for users who are seeking specifically to talk to our bot, and for us to quickly interview Oak in testing scenarios.



Pop-up Client

The primary directive of the Oak Bot is to satiate the needs of any user who has follow up questions about Hampton University. Frequently asked questions, Inquiries about departments, and travel information will ultimately be dictated by our completed product. This is why we have also integrated our bot with the hampton website directly, using a live instance of the hampton university website, and minified interface for our bot we managed to create an example endpoint for what the final integration of our site into Hamptons will be like. The bot exists in the bottom corner which is standard for integrated assistants.



There is a major drawback to utilizing Hamptons website in this manner which is unfortunately out of our control. The school's website does not have security certificates. Because of this, and a recent push by most browsers for the requirement of the HTTPS protocol, Hamptons site is blocked by the browser. There is a fix for getting past this, but it adds a roadblock to seeing our site in full.

Unblocking Hamptons Site (For Google Chrome)

--Click the information button in the top left, represented by a lock or I directly next to the URL
--Go to site settings, or click manage permissions
--Find the insecure content tab, and change it to Allow
Questions to Ask Oak

--"Who is the president of Hampton University?"
--Answer: William R. Harvey
--"What are the colors of Hampton University?"
--Answer: White and Reflex Blue
--"When was Hampton founded?"
--Answer: April 1, 1868
--"How many students are at Hampton University?"
--Answer: 3,672
Version History
Version	Date	Document
Version 1.0	02/13/2020	ReadMe

