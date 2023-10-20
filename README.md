# tgi-chat-client
A gradio client to test the TGI server hosting code-llama-2

```
 oc new-app https://github.com/bkoz/tgi-chat-client.git --name=chat
 oc create route edge chat --insecure-policy='Redirect' --service=chat
 ```
