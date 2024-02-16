# Introduction:

Sentiment analysis has emerged as a significant tool during the COVID-19 pandemic. Its
significance lies in its ability to gauge public sentiments, emotions, and perceptions, offering
valuable insights into the evolving attitudes and concerns of people amidst the crisis – all
through language/words used in the tweets made by an average user. This analysis assists in
tracking the shifts in public sentiment over time, aiding authorities in tailoring their responses
and strategies accordingly to address the changing needs and concerns of the population.
With so much info flying around during the pandemic, understanding how people feel helps
figure out what they think about different news and stuff. By doing this, we can spot where
there might be wrong or missing info that needs fixing. This is really important to help people
make good choices and stop wrong info from spreading.

When we check out how people share their feelings online during the pandemic, it helps us
see how it's impacting their mental health. This can tell us where people might need extra
support with their feelings.

For businesses, checking how people feel online is super important. It helps them change how
they sell things and make products that people really want during these hard times.
Even governments can use this to understand what people think about the rules and stuff
related to the pandemic. Knowing this helps them make better decisions based on what
people want.

When things are really tough, this way of understanding feelings helps find places or groups
of people who are feeling really bad. This way, help can go to those who need it most,
making it easier to help everyone during a crisis like the pandemic.
So, this kind of understanding feelings online has been a huge help in making decisions,
rules, and giving support during COVID-19.

# Relevance of Twitter data for sentiment analysis:

Twitter data holds significant relevance for sentiment analysis due to several key reasons.
Firstly, the platform's real-time nature offers a vast pool of diverse and current opinions,
reactions, and emotions expressed by users worldwide. This continuous stream of data
provides a rich source for sentiment analysis algorithms to track and analyze sentiments as 
they unfold, enabling near-immediate insights into public reactions to events, trends, or
topics. Additionally, Twitter's concise format encourages users to express their thoughts
succinctly, making it easier for sentiment analysis models to extract and analyze sentimentladen content efficiently. Twitter's wide user base encompasses diverse demographics and
geographies, allowing for a broader and more comprehensive understanding of sentiment
across various communities and cultures, making it a valuable resource for sentiment analysis
studies.

# Objectives:
The research objective revolves around interpreting human language within the corpus. We
want to guess what might happen or put things in groups based on how people express
themselves. Also, I am trying to figure out how words, feelings, and what happens next are
connected. I want to make sure our guesses are right and maybe make them even better for
smarter understanding.
Using what we learn from how people talk, we might help make decisions or get better at
understanding how people communicate in that area.
Corpus Methods Used:
Tokenization: Breaking tweets into individual words or tokens for analysis.
Removing Stop Words: Eliminating common words (like "and," "the") that do not carry
specific sentiment.
Stemming or Lemmatization: Reducing words to their root forms to reduce variations.
We organize and simplify the words in tweets to make them easier for computers to
understand. This includes breaking tweets into smaller parts, getting rid of common
unimportant words, and making words simpler. These techniques streamline the data, making
it more manageable and reducing noise for sentiment analysis
Looking at Word Groups: Instead of just one word, we look at groups of words together to
understand better what's being said in tweets.
Turning Words into Numbers: Computers like numbers, so we change words into numbers to
help computers understand tweets. This helps in analyzing sentiments more effectively.
Feature Extraction method like TF-IDF (Term Frequency-Inverse Document Frequency) is
chosen, for evaluating the importance of words in tweets by considering how frequently they
appear in a tweet compared to the entire corpus.
Understanding context and topics we can try to figure out what's happening in tweets by
looking at the bigger picture. This helps us understand not just feelings but also what the
tweets are about.

# Literature Review:
Research exploring sentiment analysis and text classification using Natural Language
Processing (NLP), especially concerning social media data and COVID-19, has gained
traction because of how the pandemic has affected how we share information globally. Many
studies have looked into these topics, giving us insights into how sentiments are analyzed and
how text is categorized during the COVID-19 era:

# Sentiment Analysis on Social Media during COVID-19:

Researches are made at how folks share their emotions on places like Twitter, Facebook, and
Reddit during the pandemic. Seeing how people react, what they feel, and what worries them
about COVID-19. It has also been analysed on how watching how these feelings shift over
time and among different groups of people.
Detecting Misinformation with Text Classification:
Making computer models that can figure out what's true and what's not about COVID-19 on
social media help in trying to find ways to tell apart the right info from the wrong stuff.
Sentiments' Impact on Behavior:
A few researches show how what people talk about on social media affects what others do
during the pandemic. They show if good or bad feelings change how people follow safety
rules, think about getting vaccinated, or stick to guidelines.
Looking at Sentiments in Different Languages:
Since COVID-19 affects the whole world, studies are looking at how people in different
countries express their feelings on social media in their own languages. They are trying to
understand global sentiments about the pandemic. Finding out what people think from social
media is a pretty active job. People often use English to figure out opinions, but some
scientists did something similar for Chinese. They gathered about 2270 reviews of movies.
Then, they sorted through these reviews, keeping only the ones that fit certain rules—like no
rude words, correct sentences, and only in Chinese. This made a new bunch of reviews called
the "Chinese Sentiment Treebank," all about how people feel in Chinese. So this is one way
to look at how languages can be used to decipher insights from the corpus.
Monitoring Public Health and Managing Crises:
Researches have used sentiment analysis on social media to help health groups keep an eye
on how people are feeling. This also involved trying to spot areas where people might be
really worried or stressed and want to help in emergencies.
Lots of academic groups, meetings, and research centers are working on these topics. They
have contributed to understanding how we use language technology in crises. Recently, there
has been a lot of progress in using advanced computer techniques like BERT and GPT,
showing how we can better understand what people say on social media during big global
events like COVID-19. Some researches focus on using Artificial Intelligence. The ARNN, a
part of a group of computer systems known as Recurrent Neural Networks (RNN), is used for
studying feelings in texts. RNNs are great at remembering things, and one popular type called
LSTM has a special memory cell to fix issues seen in basic RNNs. These cells can store more 
information compared to regular ones. The researchers in this study used a mix of ARNN and
LSTM to understand emotions expressed in text.
Methodology on a small corpus to understand how coding is done:
Dataset: Collection of datasets include various means like collecting the Twitter data using
public APIs like Twitter API and Kaggle datasets related to COVID-19 tweets for different
languages where privacy is maintained by removing the usernames or names and replacing
them with the numerical values for testing and training our model.
Preprocessing steps: Tokenization, stemming, stop-word removal, was done to further clean
the data to be worked upon.
Feature Engineering: I used TfidVectorizer to convert textual data into numerical data to be
used into the ML model used in further process. The TF-IDF (Term Frequency-Inverse
Document Frequency) vectorizer function is a method used in NLP to convert text data into
numerical form. By using this, it is helpful to calculate the importance of a word in a
document relative to a collection of documents (a corpus).
NLP techniques used: I used the logistic regression model for text classification and
sentiment analysis.
Visualization: I used Seaborn, Wordcloud and Matplotlib library to visualize the different
distribution of sentiment categories to extract interpretations out of them.

# Experimental Setup:
The tools and programming languages used in this project are:
Python, NLTK, Scikit-learn, Seaborn, Wordcloud, Matplotlib, Pandas, TfidfVectorizer
Environment: Jupyter Notebooks via Bulba

# Results:

The bar chart above displays the distribution of sentiment categories in the training dataset.
Each sentiment category is represented on the x-axis, while the count of tweets associated
with each sentiment is shown on the y-axis. This visualization provides a clear representation
of the balance or imbalance between different sentiment classes, allowing us to observe
which sentiments are more prevalent and which are less common in the dataset.
Wordclouds: The word clouds represent the most frequent words found in tweets for each
sentiment category within the training dataset. Each word cloud corresponds to a different
sentiment, providing a visual representation of the words that are most characteristic of each
sentiment.

From this visualizations we can infer that words like “thank”, “help”, “good”, “well”,
“support” are classified as extremely positive.
Words like “crisis”, “price”, “oil”, “grocery”, “need”, “pandemic” are classified as extremely
negative because of the grave situation under these categories during the COVID-19 times.
Sentiment Trends: From the below chart it is seen that people tried to be more hopeful and
positive when the covid era peaked in the month of march 2020. The line of being extremely
negative is always low which says that twitter consists of people (or alleged bots) who try to
have a positive outlook on life.
It is also seen to be negative during the peak time of March 2020, but not extremely negative.
Which gives us a reality check at the same time. This data is interesting to see in this way.

The line chart visualizes the sentiment trends over time based on the tweet data. Each line
represents a sentiment category, and the chart shows how the number of tweets for each
sentiment fluctuates over the dates present in the dataset.
Finally, the performance metrics of my Linear Regression model, such as accuracy, precision,
recall, and F1 score can be found as below:
In this research about understanding how people feel in tweets during the COVID-19 time,
we're using a simple method called linear regression on a small corpus dataset to do some
analysis. It helps us figure out which words or ways of talking relate to whether people feel
good, bad, or just okay. Using this method because it's easy to understand and shows us how
different words might make people feel. It also helps us quickly check a lot of tweets to see if
certain words are connected to specific feelings. While it's not the most advanced method, it's
a good starting point to learn about how words in tweets link to people's emotions during the
pandemic.

Deep Learning:
Lately, there's been a lot of interest in using advanced computer methods called deep learning
for understanding language and mining information from text. These techniques involve
training very complex models with lots of data. When people write, the text already has
things like grammar rules (how sentences are built) and meanings between words (like
synonyms or relationships). Deep learning helps create really detailed word representations
by using all this knowledge.
In past research, machine learning was directly applied in the Neural Network field to address
various challenges related to understanding emotions. This approach involves three key
methods: simple RNN, LSTM, and multilayer perceptron (MLP), each capable of handling 

complex connections. The model, influenced by social media, continuously learns from its
errors during online learning, gradually improving itself over time.
Deep learning provides diverse ways to understand data. It includes supervised and
unsupervised learning, where computers are taught or learn on their own, respectively. In
sentiment analysis, deep learning starts with feature learning, allowing systems to
independently learn and create input representations from data connections. This learning
process benefits from larger training datasets and various word embeddings.

# Conclusion:
By using libraries and tools, through this project we can understand how people felt in their
tweets during the COVID-19 time. By looking at lots of these messages from research paper
and corpus used, we can say that feelings were all over the place - some were hopeful, others
were scared or upset.

But figuring out emotions from words is hard! People express themselves in many ways, and
online messages can be tricky to understand completely.
Even though it was tough, this study helps show how we can use these computer tools to get
an idea of how people felt during the pandemic. It also tells us that we need to keep making
these tools better to really understand what people mean when they write online. Like using
In the future, as technology gets better, we'll be able to understand feelings in online
messages even more. This research helps us see how technology can help us understand how
people express themselves, especially during difficult times like COVID-19.

# References:
• M. K. Hayat et al., "Towards Deep Learning Prospects: Insights for Social Media
Analytics," in IEEE Access, vol. 7, pp. 36958-36979, 2019, doi:
10.1109/ACCESS.2019.2905101.
• K. B. Prakash, S. S. Imambi, M. Ismail, T. P. Kumar and Y. V. R.T.N. Pawan,
"Analysis prediction and evaluation of Covid-19 datasets using machine learning
algorithms", International Journal of Emerging Trends in Engineering Research, vol.
8, no. 5, pp. 2199-2204, May 2020.
• S. Chaurasia, S. Sherekar and V. Thakare, "Twitter Sentiment Analysis using Natural
Language Processing," 2021 International Conference on Computational Intelligence
and Computing Applications (ICCICA), Nagpur, India, 2021, pp. 1-5, doi:
10.1109/ICCICA52458.2021.9697136.
• H. Adamu, M. J. Bin Mat Jiran, K. H. Gan and N. -H. Samsudin, "Text Analytics on
Twitter Text-based Public Sentiment for Covid-19 Vaccine: A Machine Learning
Approach," 2021 IEEE International Conference on Artificial Intelligence in
Engineering and Technology (IICAIET), Kota Kinabalu, Malaysia, 2021, pp. 1-6, doi:
10.1109/IICAIET51634.2021.9573866.
