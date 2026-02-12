# Use plugin

## Preparing strings for translation

Before you start translating strings, you need to collect them into a file using the built-in localization system "Localization Dashboard".

* Check if "Localization Dashboard" is checked in "Editor Preferences"

![](<.gitbook/assets/image (14).png>)

* Open the "Localization Dashboard" from the "Window" menu

![](<.gitbook/assets/image (12).png>)

* This is what this window will look like.

![](<.gitbook/assets/image (3).png>)

1. Here you need to check the box in order to search for strings in the source code, you also need to specify the path to the folder with the source code
2. Here you need to check the box in order to search for strings in Blueprints, UMG and other assets of the game, you also need to specify the path
3. This is where the default language is set
4. New languages are added here, into which the game will need to be localized

* This is how the settings will look so that you can start collecting strings for translation

![](<.gitbook/assets/image (9).png>)

* To collect strings, you need to click the "Gather Text" button, a window with the search process will appear

![](<.gitbook/assets/image (13).png>)

Now that the languages you are interested in have been added and the strings have been collected, you can proceed to the translation.

## Translating strings

The plugin button is located at the top of the main editor screen.

![](<.gitbook/assets/image (8).png>)

After clicking on the button, the plugin window will open, which will display all the selected languages, except for the default language.

1. A slider that allows you to select the number of strings for translation in one request (maximum 128)
2. Language displayed (Culture)
3. The progress bar displays the number of translated strings , but only after clicking on the "Update progress bar" button
4. Button for translating strings
5. Button to update the progress bar

{% hint style="warning" %}
Due to the limitations of the Google Translate API, an error may pop up when too much text is sent for translation, you will need to reduce the value of "Max Strings in one request".
{% endhint %}

![](<.gitbook/assets/image (2).png>)
