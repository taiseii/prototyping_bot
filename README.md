# prototyping_bot
application specific bot with an example of deployment using flask
<h1>Simple application specific chat bot</h1>
<p>inspired by Tech with Tim( credit to : https://www.youtube.com/watch?v=wypVcNIH6D4)<br>
Difference between the original tutorial and this example are:<br>
1. NN model created using TensorFlow 2.0 'layers' and 'model' API instead of TFlearn<br>
2. Include deployment example of the app using Flask<br>
3. Tryed out different bag of words scoring ( credit to : https://towardsdatascience.com/3-basic-approaches-in-bag-of-words-which-are-better-than-word-embeddings-c2cbc7398016 and https://github.com/makcedward/nlp/blob/master/sample/nlp-bag_of_words.ipynb)
</p>
<h2>Disclaimer</h2>
<p>NN model here in overfitted to the dataset and further callibration is needed with more data.<br>
This is just an example of how one can create simple chatbot and deploy it</p>

<h3>Prototyping example</h3>
<p>look at "chat bot prototype.ipynb"</p>

<h3>Deployment example</h3>
<p>look at https://github.com/taiseii/my_page/blob/master/flaskApp/chat_bot_model.py and https://github.com/taiseii/my_page/blob/master/flaskApp/routes.py
, and https://github.com/taiseii/my_page/blob/master/flaskApp/templates/chat_bot.html</p>
