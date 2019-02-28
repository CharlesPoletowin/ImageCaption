# ImageCaption
paper, show and tell, Google, CVPR 2015 

This is a demo for image caption.
I don't create the evaluation code.
If you want to use it, first using download.sh to get the data needed. It will automatically create a directory and download the coco data.
Then using the build_vocab.py to build the vocabulary we need.
After that, use the resize.py to resize all the pictures into the same size. Meanwhile, I also recommend you to use it to resize the test picture.
What's more, use the train.py to train the model. Please adjust the configure by adding the flag or just revise the code for both num_epochs and batch_size。
In the end, you can use sample.py to create the demos for image caption.

I use this code in Google Drive colab with free GPU and even TPU in 12 hours continully.
