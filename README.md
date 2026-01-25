# SagmanOllamaAI
[Open My Ai Ngrok](https://sagmanua.github.io/SagmanOllamaAI/)
[Open My Ai CloudFlared](https://sagmanua.github.io/SagmanOllamaAI/index1.html)  
This repo is used to crete ai on hostnig (and use power of google to trian ai)

## How to setup this Ai 
You have 2 way i with NGROK and another one with CloudFlared
### NGROK
To setup with NGROK you need to create NGROK acount where you need to taky autokey  [You can get this ](https://ngrok.com/)
And that you add this key in Google colab  
Next step just run this colab 
[My setup for this ai ](https://colab.research.google.com/drive/1GLFaDFWv1bjayIb621JZImJFWmiV_9FX?usp=sharing)  
### CloudFlared
In this way you just need to setup Google Colab
[My setup for this ai ](https://colab.research.google.com/drive/1sAJ8iSGXE7aaaRksYgfpeAO36G5hgrhO?usp=sharing)  

### Next Step
after do all this thing you need to change url of conexion 

After setup Ai (one of way) you need to change url in codigo

On line 40 change Url to your Url that apear at `print(f'export OLLAMA_HOST={ngrok_tunnel.public_url}')`
```
const ollama = new Ollama({ host: '[Your url]' });
```









