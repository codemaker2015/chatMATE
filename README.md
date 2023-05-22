# ChatMATE - Chat Multi-purpose AI Technology
This app is an LLM-powered chatbot built using Streamlit and HugChat.

[HugChat](https://github.com/Soulter/hugging-chat-api) is an unofficial port to the [HuggingFace Chat](https://huggingface.co/chat/) API that is powered by the [OpenAssistant/oasst-sft-6-llama-30b-xor](https://huggingface.co/OpenAssistant/oasst-sft-6-llama-30b-xor) LLM model.


## Demos

![demo](demos/demo.gif)

## Run the app
- Install the dependencies
```
pip install -r requirements.txt
```
- Run the `app.py` using the following command
```
streamlit run app.py
``` 

## Libraries used

This app is built using the following Python libraries:
- [Streamlit](https://streamlit.io/)
- [HugChat](https://github.com/Soulter/hugging-chat-api)
- [OpenAssistant/oasst-sft-6-llama-30b-xor](https://huggingface.co/OpenAssistant/oasst-sft-6-llama-30b-xor) LLM model

## How to Get Cookies ?
- Install the Cookie-Editor extension for [Chrome](https://chrome.google.com/webstore/detail/cookie-editor/hlkenndednhfkekhgcdicdfddnkalmdm) or [Firefox](https://addons.mozilla.org/en-US/firefox/addon/cookie-editor/)
- Go to [HuggingChat](https://huggingface.co/chat) and login
- Open the extension
- Click Export on the bottom right, then Export as JSON(This saves your cookies to the clipboard)
- Paste your cookies into a file `cookies.json` in the root folder