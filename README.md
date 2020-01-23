# StoryTeller
Text-generating Neural Network, trained on Fairytales by The Brothers Grimm and Alice's Adventures in Wonderland by Lewis Carroll.
<br>
GPU connection is highly recomended for taining, as it may take over 10 hours to train on CPU.
<br>
<br>
<b>Text files were generated from:</b>
<br>
Fairytales: https://www.gutenberg.org/files/2591/2591-h/2591-h.htm
<br>
Alice: http://www.gutenberg.org/files/11/11-0.txt
<br>
<br>
<b>IMPORTANT NOTES</b>
<br>
Please replace the following varibles in the notebook with the .txt files in the repository,
<br>
as this notebook links to my own Google Drive.
1. fairytales_url : ensure it links to FairytalesByTheBrothersGrimm.txt
<br>
2. alice_url : ensure it links to AlicesAdvanturesInWonderland.txt
<br>
3. checkpoint_url : any location to save model's checkpoint after training
<br>
<br>
<b>
Got lots of help with the word embeddings from Pytorch:
</b>
<br>
https://pytorch.org/tutorials/beginner/nlp/word_embeddings_tutorial.html#exercise-computing-word-embeddings-continuous-bag-of-words
<br>
<b>
Extra help regarding Google Colab's GPU connection:
</b>
<br>
https://www.kdnuggets.com/2018/02/fast-ai-lesson-1-google-colab-free-gpu.html
