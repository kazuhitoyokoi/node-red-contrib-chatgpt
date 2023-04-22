node-red-contrib-chatgpt
=====================

Node-RED node to access the ChatGPT API

## Install

Run the following command in your Node-RED user directory - typically `~/.node-red`

        npm install node-red-contrib-chatgpt

## Usage
1. Get the API key from the OpenAI API portal (https://platform.openai.com/account/api-keys)
2. Add the API key to the ChatGPT node property

![](https://raw.githubusercontent.com/kazuhitoyokoi/node-red-contrib-chatgpt/main/property.png)

3. Pass the text via `msg.payload` to the ChatGPT node

![](https://raw.githubusercontent.com/kazuhitoyokoi/node-red-contrib-chatgpt/main/flow.png)

And then the ChatGPT node will output the answer.

## Demonstration
[Smart Speaker using ChatGPT](https://twitter.com/kazuhitoyokoi/status/1649433078681464840)
