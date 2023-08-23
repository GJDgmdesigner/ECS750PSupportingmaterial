# ECS750PSupportingmaterial
This repository contains the supoorting materials for Jiadong Guo's MSc project.
My project software includes 4 executable files, they are all Juypter Notebook documents, they can be executed in Visual Studio Code, Juypter Hub, Kaggle. I recommend to run my programs in Kaggle. 

Tips: if run in Visual Studio Code, Juypter Hub, some packages may need to be installed, like seaborn, pandas, wordcloud, etc. In different situations, the dataset path may needs to change.

The source code part includes 4 Juypter Notebook documents. They are:
1) 01-tweet-comment-processor.ipynb :  It is a program that I used to process the downloaded JSON twitter comment from Postman, and store the processed dataframe in CSV files in date unit.
2) 02-sentiment-analysis-nlp.ipynb : It is the program that I used to do the sentiment analysis on the data I got from 1), and save the sentiment count result and sentiment analysis result to CSV files.
3) 03-sentiment-plot-data-contact-count-figure.ipynb : It is the program that I used to do the result Visulization. It can plot the sentiment analysis count results proportion figure, plot the the daily tweet count figure or the daily steam player count(average) figure, and concat those processed Twitter comment files which in the same date, or concat all comment files for most influential user analysis.
4) 04-influential-twitter-account-analyzer.ipynb : It is the program that I used to do result visulization and top user analysis. It can get the 20 most influential users based on the number of tweets they have posted and print their names, and plot different dates Word cloud figure.

There are five dataset folders in my support material. They are:
1) callofdutytwittercomment : The dataset that used to store the JSON format Twitter comment documents that downloaded from Postman.
2) twitter-entity-sentiment-analysis : The dataset from Kaggle, contains the sentiment analysis model training dataset and validation dataset.
3) processed-twitter-comment-2 : The dataset that used to store the CSV format Twitter comment files that transformed from callofdutytwittercomment.
4) mwii-twitter-comment-3 : The dataset that used to store the CSV format Twitter comment with the sentiment analysis result that transformed from processed-twitter-comment-2. There is alao contains all sentiments count CSV file.
5) result: Store the results of the most influential users analysis, also includes the original formula rank result and modified formula rank result.
