# Video Game Checkout System
https://plankton-app-wc2af.ondigitalocean.app/ 
Note: I was unable to change the domain of my website on digital ocean, so I was unable to use the a4-kpanneton format.

The goal of my application is a system where users can check out and place holds for various video games, similar to a library but for games instead of books. This is a modified version of my library from A2, but instead of a book checkout system I changed it to video games in order to make it more unique.

Some challenges I faced in realizing the application was defintely figuring out how to do the add, delete, and modify functions using MongoDB. Connecting to the database and setting up the user login system wasn't that hard to figure out, but figuring out how to store the data as an array and then have the array changed was challenging to figure out. I really struggled with this part, but was eventually able to get all three working, though if I had more time I may have may the interface more clear.

The authentication strategy I chose to use was creating a single test user with a test password that can be used to access the database. The username is "kpanneton" and the password is "test123". I used this method instead of allowing the user to create an account was that this was all I was able to do in the time given. If I had more time I would like to add a create account feature that will let the user make a new account on the login page.

For my CSS framework I used NES.css because I enjoyed the font style and the way the mouse turned into a pixeled glove pointer. It gave me nostalgic vibes and I think anyone using the website can feel that. Some modifications I made to the CSS framework were some changes so the styling of the background and text, by changing the color and size. I wanted to background to be black because I think dark mode websites are easier on the eyes, but was unable to get it to work on the final site. I was also struggling to fix the spacing of items on my page so the bottom display is a bit strange to read, but the functionality works.

The five Express middleware packages I used were body-parser, cookie-session, connect-timeout, handlebars, and response-time.
- body-parser: Parses the JSON.
- cookie-session: Stores the cookies for the current session of the user.
- connect-timeout: Times out the server's session after a specific instance of time, in this case it is set to 5 seconds.
- handlebars: These are used to connect the HTML elements with the server.
- response-time: Records the response time for the server's HTTP request.

# Technical Achievements
- Tech Achievement 1: Instead of hosting my website on Glitch, I used DigitalOcean. This was easier because it could pull directly from my GitHub repo.
- Tech Achievement 2: I achieved 100% in all four lighthouse tests on both of my website pages. Screenshots are provided in the "GoogleLighthouse" folder.

# Design/Evaluation Achievements
- Design Achievement 1: I followed the following tips from the W3C Web Accessibility Initiative:
1. Provide informative, unique page titles: Each page has a title that diferentiates it from the other.
2. Provide clear instructions: My website provides instructions for how to submit a hold and input information.
3. Keep content clear and concise: Only necessary information is provided on the page such as the input fields in the form, the submit button, and simple instructions.
4. Provide easily identifiable feedback: When the user leavs a field blank or puts improper inputs, they are notfied.
5. Ensure that interactive elements are easy to identify: The only interactive elements are the calender to select the date, and the submit, add, delete, modify buttons. They are all clearly labeled.
6. Provide clear and consistent navigation options: The page is pretty simple to navigate, there are minimal pages to make it easier for the user to interact with.
7. Create designs for different viewport sizes: The page adapts to different devices, creating different spacing for different devices.
8. Associate a label with every form control: Each form element on the page has a corresponding label.
9. Identify page language and language changes: The primary page language is denoted at the top of all my html files, in the header using the lang atribute.
10. Reflect the reading order in the code order: I have written my HTML code in order of what the user will be reading on the page, including CSS in a completely seperate file for increased readability.
11. Write code that adapts to the user’s technology: My code adapts the size of the screen to fit on their device, such as desktop, mobile, etc.
12. Ensure that all interactive elements are keyboard accessible: All my text input fields provided in my form are keyboard accessible. 