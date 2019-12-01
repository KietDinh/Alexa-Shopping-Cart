# Alexa_Shopping_Cart

Step 1: Go to Amazon developer services https://developer.amazon.com/ and click Alexa. You're going to have to create an account                    (its free!) Once you've created your account you should be on the Alexa developer console.

Step 2: On the Alexa developer console there should be a blue button that says create skill. Click that. Now it should ask you for a skill          name. I named it Shopping Cart, i think you can name it whatever you want, but to be safe I'd call it Shopping Cart too. After            you've named it, where it says "Choose a model to add to your skill" click custom, and below that where it says 
        "Choose a method to host your skill's backend resources" click Alexa-Hosted (Node.js). Then go back up to the top of the page and          click create skill. It takes it a minute or two.

Step 3: Now you'll be on a page with a video in the middle, on the right it says Skill builder checklist, and on the left it is a list of         fancy words like interaction model, utterance conflicts, invocation, etc. First, On the left click "Invocation". Then in the              "Skill Invocation Name" box type shopping cart. Next towards the bottom of the fancy word list you should see JSON Editor, its            right above interfaces. Click JSON Editor. That should bring up a code window. Replace the code in that window with the JsonEditor        code in this repository. Then click Build Model at the top. Wait until its finished and then Click "Code" at the top.

Step 4: On the Code page you should see three files "index.js", "package.json", and "util.js". Replace each of those with the code in this        repository and then click deploy.

Step 5: Once it finishes deploying you should be ready to test. Click "Test" at the top. Now make sure that                                       "Skill testing is enabled in : " Development. Then where it says type or click type start shopping cart. Now you can try adding or          removing stuff from the cart.
