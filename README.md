# Sentiment Analyzer of positive, negative and neutral comments using Stanford NLP Core module in Java using Functional Programming.

To get started:
- Java 17, or update the pom.xml accordingly (and change the code)
- Maven installed and active, using said Java 17

Run:

´´´
mvn clean install
´´´

Model Prediction Results:

Neutral sentiments:

SentimentRecord[name=Neutral, value=2, sentence=You've given me a lot to think.] 

SentimentRecord[name=Neutral, value=2, sentence=Do you prefer regular Java over them or how do you feel about it?] 

SentimentRecord[name=Neutral, value=2, sentence=Please Increase the font size.] 

SentimentRecord[name=Neutral, value=2, sentence=Hello how can we connect headset on online server ?]]

Negative sentiments:

SentimentRecord[name=Negative, value=1, sentence=When I'm forced to do web frontend stuff, I prefer to use VS Code, though.]

SentimentRecord[name=Negative, value=1, sentence=The IDE is getting annoying with their push to cloud based and collaborative development.]

SentimentRecord[name=Negative, value=1, sentence=I know there are ways to avoid all the issues, but I have to do this every time I setup a new machine or switch environments.]

SentimentRecord[name=Negative, value=1, sentence=Did not use to feel like this, it only started in my 50s.]

Positive sentiments:

SentimentRecord[name=Positive, value=3, sentence=I have been using Tabnine for some time and love it.]

SentimentRecord[name=Very positive, value=4, sentence=Awesome content.]

SentimentRecord[name=Positive, value=3, sentence=Edit: just finished watching, it's so sweet that you appreciate all the activity on your 
channel so much, I'm sure you'll keep getting more and more!!]

SentimentRecord[name=Very positive, value=4, sentence=Great content, very useful, thank you!]
