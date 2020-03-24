# Bengali.AI
Classify the components of handwritten Bengali

This is my first attempt at computer vision, and it was fascinating.
Before the start of this competition, I didn’t even know what pytorch is, I had a little experience of Tensorflow and Keras and it was a fascinating journey.
 
My best attempt came a few days before the end of the competition:
- Private Score 0.9219, Public Score 0.9678, my place~600 33%
- Top 10% score .09630 205 place
- First place 0.9762
 
I've tried a lot of things:

- different models
- argument
- image size and other….
 
My mistake that I encountered and for a long time could not cross the line at 0.92LB was model.eval (). 
When I trained the network train and validated, I used model.train and eval, but when I loaded the saved model, I didn’t use (eval), 2 weeks have sunk into oblivion and with it a bunch of everything has been tried.
 
I basically didn’t use other people's kernels (I didn’t make a prediction) because the goal is knowledge.
 
I used one model (b3 & 3outs) without additional data, image size 128 * 128, all data, 4 folds of 20 epoches each, and catmix.
 
 I do not have a GPU and I used only kaggle and colab.
 
All this is a long time from here such a small number of epoches, and here I fell into the trap of the fact that for tests so that I would be faster I did not use all the data and a different image size and predicted this.
 
And since I did not know the reason for my hitch, I tried a lot of everything, and when I found an error, I had time to just teach the model and add same argumentation.
I am more than sure that I did not finish the model.
This is a mass of emotions of success and disappointment, but it's great, I learned a lot thanks for this kaggle.
