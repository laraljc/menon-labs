# menon-labs
# Initial Thoughts
 - It's quite easy to get lost in the large amount of data supplied from Facebook when initially exploring
 - I thought it would be interesting to focus on my messages from Facebook Messenger since it is my primary means of communication
 - I wanted to know what my texting language comprised of, which slang words were more prominent in my everyday speech, and overall who I talked to the most
 
# Data Cleaning Process
 - Since the data was downloaded from Facebook as in JSON form, I used pandas read_json method to read messages into participants dataframes and message dataframes
 - Looking at the message data, there were a lot of strange characters so I removed all special characters, leaving only alphanumerics, and converting all text to lowercase
 - Then I expanded each content column of the message data since it contained sentences and I wanted to view frequencies of words
 - Counted the values of each word
 - Compiled a list of the 100 most frequently found words in written English sourced from Wikipedia and additional words that I found I used a lot that weren't particularly interesting

# Data Visualization
 - Thought it would be interesting to create a word map with a facebook logo mask highlighting the knowledge facebook obtains about you
 - With your messages, Facebook essentially knows how to recreate or potentially mimic you text/speech patterns

# Further Steps
 - A more impactful image could be using the user's profile picture as the mask with their speech creating the image of themself
 - Showing language change over time and incorporating timestamps
 - Showing categories of topics you discuss based off of your messages
 - Friend clusters from friends who frequently appear in group chats together
 - Determining the friends you like more than they like you or vice versa (they send you more messages than you send them)
 
# Challenges
 - Majority of the time was spent on data cleaning as the Facebook dataset is quite large and has discrepancies all across
