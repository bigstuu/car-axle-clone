# Bookmarklet Bypasses

## Basic Methods

### Devtools

Even though it is likely blocked on your computer, it is still worth a shot.

#### Requirements

-   Devtools
-   A place where you can store text (So you can use it easily)

1. First you will want to copy the built code from your selected version. Here are the links to them
   v7: (Not released yet so don't expect this link to work)  
   https://raw.githubusercontent.com/car-axle-client/car-axle-client/v7/dist/build.js  
   v6: (Latest Version)  
   https://raw.githubusercontent.com/car-axle-client/car-axle-client/v6/dist/build.js

2. Now store this somewhere safe (in a text file or something).
3. Open Devtools on the desired website
4. Go to the console tab
5. Paste the code and press enter
6. You should see the car axle client GUI open.

-   Please note that this wont work on some websites!

### about:blank Injector

Works on mkost school blocking plans which is good for you and me.

#### Requirements

-   Have the website not be apart of the block list

1. Go to this website [injector](https://penguinify.github.io/javascript-injector)
2. Press inject car-axle-client
3. You should see an about:blank page open and the gui should open as well

-   This may not work depending on how your school handles things

### Self-Hosting

Host it on a website so its not a bookmarklet, its a website (kinda).

#### Requirements

-   A brain (any will do)
-   A github account

-   BTW any website that supports static webpages works here, it doesn't have to be github
-   If you want to host the games yourself hmu on discord (@penguinify)

1. Create a github organization that is the name of your website
2. In that organization make a repository called {ORGANIZATION-NAME}.github.io
3. Download this file or any version you want. (You just need a js file with the source code)  
   v7: (Not released yet so don't expect this link to work)  
   https://raw.githubusercontent.com/car-axle-client/car-axle-client/v7/dist/build.js  
   v6: (Latest Version)  
   https://raw.githubusercontent.com/car-axle-client/car-axle-client/v6/dist/build.js
4. Upload it to said repository
5. Create an index.html file in the repository with this code:

```html
<script src="build.js"></script>
```

6. Wait for a few minutes
7. Go to {ORGANIZATION-NAME}.github.io
8. You should see the car axle client gui when you go to the website.

#### Ublock Orgin

A nice and elegent solution

#### Requirements

-   Have ublock orgin (https://chromewebstore.google.com/detail/ublock-origin/cjpalhdlnbpafiamejdnhcphjbkeiagm)

1. Open ublock settings. (Press the extension icon and click the settings icon)
2. On the bottom press "I am an advanced user" then click the cog icon
3. Change the userResources from unset to `https://pastebin.com/raw/PPZ1T7uh`
4. Go back to the main extensions pages and click on My filters button.
5. Open a new webpage and press ctrl alt tilde (ctrl+a+~)
6. Paste in the car axle client src code, as desccribed above.
