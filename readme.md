# Pond Chicken's Twitch Clip Player
A Simple Twitch clip player designed to be used by streamers who want to be able to emded their clips in a SLOB/OBS scene.

It supports playing either random clips or your top clips and offers the following feature found on certain paid services:

1. Supports up to 1000 clips
2. Allows you to limit the clips to those created by specific Twitch users
3. Allows you to overlay scan lines on your videos for that old school CRT look
4. Allows you to add static between videos
5. Allows you to display the name of the user who created the clip.

## Setup
You are required to create a Twitch developer application in order for this to function.
If you have already created one and have the Client ID and Client Secret, skip to Step 8.

1. Visit https://dev.twitch.tv/ and Login.
2. Press "Your Console" in the top right.
3. Under "Applications" press "Register Your Application"
4. Give it any name, it doesn't matter. Select the most appropriate category, or just "Other."
5. As an "OAuth redirect URL" is required, enter a link to any website - preferably one you own, or just enter a link to google (https://google.com/). **The app doesn't use this so it's not important.**
6. Press "Create"
7. Once created, press "Manage" and scroll to the bottom of the page. **Take note of the "Client ID" and "Client Secret"** (press new secret if there isn't one there)
8. Now, download the this project and place it in a folder on your Computer
9. Open the `index.html` in your browser and then follow the setup steps 