# BLOCKBUSTER OR BUST

Welcome to the CS109 final project for Stephen Albro, Alpkaan Celik, Jason Dong and Jessica Li! <br><br>

Access our website here - [Blockbuster or Bust](http://google.com) <br>
Access our screencast video here - [Blockbuster or Bust Video](http://google.com)

## Getting started

In this repository you will find our process project book - [Process_book.ipynb](./Process_book.ipynb). <br><br>

This process book explains:
* Overview and motivation for our project
* Initial quesitons that we were looking to answer
* Our original attempt to answer this question is referred to in this process book, and can be found in the notebook [Project_attempt_1.ipynb](./Project_attempt_1.ipynb)
* Data analysis and decision making process

Because of our large dataset, alot of the code in the process book can take a long time to run so we often save our data to .json files and have loaded them into the repository so that you can simply call them into the process book (please note, that files larger than 100MB have been uploaded to dropbox). 
* [newBOM.json](./newBOM.json) contains the box office data we scrape from [Box_Office_Mojo](http://www.boxofficemojo.com)
* [complete_valence.json](https://www.dropbox.com/s/xxiojklc9coakkx/complete_valence.json?dl=0) contains the scraped IMDB review data merged with valence values and box office data
* [dftouse.json](https://www.dropbox.com/s/ieu8sbn1c4eo2bv/dftouse.json?dl=0) is the complete_valence.json data adjusted for inflation
* [review_parts.json](https://www.dropbox.com/s/1hnm9wbyhuiur1z/review_parts.json?dl=0) contains the parts of text after natural language processing
* [vocab_unique.json](./vocab_unique.json) is a preliminary list of unique nouns
* [vocab_unique_2.json](./vocab_unique_2.json) is a truly unique list of nouns
* [corpus.json](https://www.dropbox.com/s/3z3bpbujcq60ate/corpus.json?dl=0) is the corpus for LDA
* [adj_unique.json](./adj_unique.json) is a preliminary list of unique adjectives
* [adj_unique_2.json](./adj_unique_2.json) is a truly unique list of adjectives
* [Xarray.json](./Xarray.json) is the Xarray used for sentiment analysis
* [resparray.json](./resparray.json) is the response array created from the valence scores
* [logpositives.json](./logpositives.json) is the dictionary of positive probabilities
* [lognegatives.json](./lognegatives.json) is the dictionary of negative probabilities
* [reviews.json](./reviews.json) is a dictionary of the review ids
* [reviewdict.json](./reviewdict.json) is a dictionary with key review id, and value a list of dictionaries
* [completedf_intermediate.json](./completedf_intermediate.json) is a preliminary dataframe that we make
* [complete_byreviews.json](https://www.dropbox.com/s/1j8dj02ifsbpumv/complete_byreviews.json?dl=0) is a dataframe by reviews with the sentiment analysis scores

