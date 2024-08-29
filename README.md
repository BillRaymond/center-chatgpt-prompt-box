# Center and stylize the ChatGPT prompt box
⭐️ This repo, if you find it useful!

![](chatgpt-center-chatbox-demo.gif)

## Purpose
If you deliver ChatGPT training videos (live or recorded) and your browser is full-screen, you know, subtitles or ads usually overlay the prompt.

The solution? Move the prompt to the center of the screen!

## Installation
1. Install the [Tampermonkey](https://www.tampermonkey.net) extension for your browser of choice (I only tested Safari on the Mac)
2. With your browser running, run Tampermonkey and create a new script
3. Replace the default code Tampermonkey creates with the code on my site
4. Save the Tampermonkey code

## Usage
1. Go to https://chatgpt.com
2. When the prompt is in focus (meaning you select the text area or it is already selected), it will display in the middle of the page with a colorful background so it stands out
3. Type your prompt and press enter/return on your keyboard (you can even use shift-enter for longer prompts!)
4. If the prompt box is in your way, select an area outside the box, and it will go back down to the bottom of the page where it exists by default

## Known limitations
At the moment, the following functionality does not work, mostly because I did not have the time to figure it out:

1. Pressing the button to attach a file will revert to the standard ChatGPT interface. The workaround is to drag and drop files into the chat space.
2. Pressing the send button (the up arrow) will return you to the standard ChatGPT interface. Instead, press the return or enter key on your keyboard.

## License
This code is free to use. 
If you do share the code, I would appreciate a mention:
* @BillRaymond
* https://github.com/BillRaymond
* https://github.com/BillRaymond/center-chatgpt-prompt-box

## PRs
If you make improvements or variations and feel like sharing them, please send a standard PR letting me know what changes you made and why.

## Liability
I claim no liability for this code or its supporting tools. When using ChatGPT, your browser will run a third-party extension (Tampermonkey) with which I have no affiliation. Tampermonkey then injects code into your browser using the content the browser is displaying. 
