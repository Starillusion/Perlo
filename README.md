Perlo is a medium-sized chat server that can be used for many purposes, such as chatting with friends at a big house that yelling or running isn't a 
option, another use is hiding communications from a person but you don't want to whisper because it is suspicious. The purpose is yours to decide,
but there is a little bit of setup needed!

 • Step 1: Clone this repository (if you haven't already) to a destination such as your user account folder (usually under C:\User\myUser).

• Step 2: Open the Perlo directory, go into the folder **server**, then use Notepad or Nano (on Linux) to open the **config.json** file.

• Step 3: Look for the **masterpass** property and change it to your desired passwor. **IMPORTANT: Leave the quotes in, type in between them**

• Step 4: Close and save the file, then go to the **env** directory, and open the **CurrentAdmin** file. This tells Perlo what user is the server
                administrator, so set it to a name of your choice. **Note: You'll need this name for the next step, so keep it on hand.**
 
• Step 5: You're almost done, but you'll need to do something that most other instructions don't ask for - change into the main directory
                and launch Perlo **before the setup is finished**, since the **CurrentAdmin** points towards a nonexistent user, **don't do anything
                that makes the code open that file.** To launch Perlo, simply type **./launcher** while in the root of this repository, and watch it come
                online. It doesn't look like much, but open your browser and go to **localhost:1501**. It **will** give you a 'unknown certificate' warning,
                but this one is safe to add a exception for. Do that, and you are presented with a web page. Here's something: can you see the Username
                or Password boxes? No, they are invisible **until** you mouse over them! That's a little magic of CSS (hence my profile bio)! Do you still
                have that name for the **CurrentAdmin** file? Type it into the username box, and then decide another password (not the same the the master
                pass!) Scroll down unless you already see the **Login** and **Create New User** buttons, then click/tap the** Create new user** button.
                Look back on the terminal and you'll see text printing out over your user creation. Switch back to the browser and you'll see the login part
                of the page is gone and there is now a near-invisible text area, a text box under that, and a **Send** button under that. Type your message 
                into the textbox, hit Enter/Return or the **Send** button and it will appear along with the server's time in the text area. Anyone else using
                this would see your message!

• Step 6: You're done! Now go chat with some friends....

Note: Some modules included in Perlo can be copied and used in **your projects!** (under **server/lib**)
