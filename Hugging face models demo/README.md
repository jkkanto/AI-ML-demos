# Hugging face models demo

Because building a decent nn-model from scratch takes a lot of time and money, it's better to use existing ones. One of most popular place for models and datasets is Hugging Face. Here are a few examples of using existing HF-models:

* Translator (en-fi, fi-en) (Translator.ipynb)
	* Using OPUS - Open neural machine translation models
	* Model source https://huggingface.co/Helsinki-NLP/opus-mt-en-fi
* Text-to-image (Text-to-image.ipynb)
	* Based on stable diffusion method
	* Model source https://huggingface.co/runwayml/stable-diffusion-v1-5
* Text-to-image with prompt (Text-to-image with prompt.ipynb)
	* This one uses a face image as a prompt for stable diffusion
	* Based on paper "IP-Adapter: Text Compatible Image Prompt Adapter for Text-to-Image Diffusion Models"
	* Model source https://huggingface.co/h94/IP-Adapter-FaceID
* Image-to-text (Text-to-image.ipynb)
	* Image captioning model trained in flax 
	* Model source https://huggingface.co/nlpconnect/vit-gpt2-image-captioning
* Visual question answer (Visual question answering.ipynb)
	* Based on paper "ViLT: Vision-and-Language Transformer Without Convolution or Region Supervision"
	* Model source https://huggingface.co/dandelin/vilt-b32-finetuned-vqa
