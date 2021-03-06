# Text Generation with ML/Recurrent Neural Networks (RNNs)

- UCSD Digital Humanities Research Group. 
- Time: Friday April 25, 2:10-4pm
- Location: Quince Room, Geisel Library, UCSD
- Robert Twomey (rtwomey@ucsd.edu) [roberttwomey.com](roberttwomey.com)

## Description
This workshop will explore the use of neural networks for text generation. We will discuss a case study, OpenAI’s GPT-2, and then work through hands on examples with char-rnn (an LSTM recurrent neural network RNN), training it on custom data. 

NOTE: Please bring a textual corpus to train your model on! (SMS messages, nature documentaries, transcriptions of your childhood journals)

## References: 

- Case Study: GPT-2 
  - Better Language Models and Their Implications - https://openai.com/blog/better-language-models/
  - The AI Text Generator That’s Too Dangerous to Make Public - https://www.wired.com/story/ai-text-generator-too-dangerous-to-make-public/
- Bonus Reading:
  - https://www.theverge.com/2019/2/14/18224704/ai-machine-learning-language-models-read-write-openai-gpt2
  - Some pretty impressive machine-learning generated poetry courtesy of GPT-2 https://boingboing.net/2019/03/15/digital-lit.html
  - Identifying GPT-2 generated text: https://boingboing.net/2019/03/08/gpt-2-vs-gpt-2.html
  - “I still think GPT-2 is a brute-force statistical pattern matcher which blends up the internet and gives you back a slightly unappetizing slurry of it when asked", https://slatestarcodex.com/2019/02/19/gpt-2-as-step-toward-general-intelligence/
  - https://towardsdatascience.com/too-powerful-nlp-model-generative-pre-training-2-4cc6afb6655
- Char-RNN, the model we are using today: 
  - Andrej Karpathy, The Unreasonable Effectiveness of Recurrent Neural Networks 2015 - http://karpathy.github.io/2015/05/21/rnn-effectiveness/

## Setup
1. Log into [jupyterhub.nautilus.optiputer.net](jupyterhub.nautilus.optiputer.net), and spawn a new image: ![alt_text](https://raw.githubusercontent.com/roberttwomey/text-gen-dh/master/images/jupyterhub_launch.png "Login Screen")
2. Inside of JupyerLab, start a new terminal: ![alt_text](https://raw.githubusercontent.com/roberttwomey/text-gen-dh/master/images/launch_terminal.png "Launch Terminal")
3. Clone this repository: 

```git clone https://github.com/roberttwomey/text-gen-dh/```

4. Open the folder and let's work through the jupyter notebooks!
