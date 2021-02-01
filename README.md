# Project Dog Vision!

This is a project I've done to learn how transfer learning works and some basics of deep learning.

What does it do: Recognizes the breed of a dog. So I've used the Kaggle's dog breed identification [dataset](https://www.kaggle.com/c/dog-breed-identification/data#)

What I've learned:
  * Using Colab.
  * To visualize the data.
  * Preprocessing the images.
  * Building, training, evaluating a model.
  * Making predictions.

I want this project to be useful for any kind of person (for eg, someone with no programming background). 

Since the model was made with TensorFlow, I can't expect a person ( with no experience in programming) to install `Python`, `TensorFlow`, `NumPy`, `Matplotlib` etc for using this project.

So I've decided to make a Colab Notebook where all you have to do is paste the image URL and run the code, simple as that. But there was a problem, "what if I want an image which is on my PC?". So I've researched on "how to import an image from PC directly to Colab runtime" and sadly I couldn't find a way. 

BUT however I've found another way, *uploading the image to a temporary cloud storage!*

<img src="https://nyc3.digitaloceanspaces.com/memecreator-cdn/media/__processed__/518/template-yeah-this-is-big-brain-time-1619-0c6db91aec9c.jpeg" align="center" height="191" width="340">

So work to be done:
  * Get all the required libraries ready. ✅
  * Use the pre-trained model and make some predictions to make sure everything is working fine. ✅
  * Find a way to download the image and *try* to store the image name/path in a variable so that the user doesn't have to edit much code. ✅
  * After completing a fully working Colab notebook, try and make code for users who want to do this whole process locally in their PC.
