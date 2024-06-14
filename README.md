# App Review Model -- Natural Language Processing
As mentioned in the description, this was a natural language processing (binary classification) model that I built to read through app reviews from the Amazon Kindle. It scored an 85 percent on the testing data, which I found quite good considering the only metric it was given was words, and no user information. Because this is a bag of words model, the down-side is that it does not necessarily consider the context in which a word occurs, which allows room for this architecture to be greatly improved; regardless this was promising.

I find it fascinating how NLP models continue to evolve... and this project was an awesome learning experience. I will definitely create more NLP models in the future, as I am currently working on a much larger one that I currently cannot post, but I will try to keep you all posted on it. Thanks for checking this out!

UPDATE: I recently uploaded the model itself (the .pth file) if any of you guys would like to use it yourselves! I will do my best to update my models going into the future, and also upload .pth files with all of my notebooks so everyone can use them for free and test them out. My most recent update to this model in particular was just some optimization, as I noticed the model was overfitting a little bit, so I lowered the epochs and applied some dropout layers which helped substantially.

My next update will likely be some form of multiclassification or an update to a recursive neural network architecture. There is also a possibility I mess around with some transformers. Stay in the loop!

I did not scrape this dataset; it uses MIT licensing -- the link is here if you wanna check out the creator(s): https://www.mit.edu/~amini/LICENSE.md 
