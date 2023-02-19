# Name classifier
Used a Recurrent Neural network to classify last names into one of eighteen languages of origin
<br>
Used a txt file to read in the words from each of the 18 languages of origin.
<br> 
A RNN was used on a charachter by charachter basis, with each step in the training loop indicating the following letter in the word and an updated hidden state.

Hosted on hugginface using Gradio as the interface
# classify PY file in action

Console

![lastNames](https://user-images.githubusercontent.com/53010808/136102540-8e98878e-2393-4827-90bc-d9618e276104.PNG)

Gradio application hosted on huggingface

![gradioNames](https://user-images.githubusercontent.com/53010808/219978722-06013904-e2ab-4533-b08d-8ba48351816f.PNG)
