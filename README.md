# DeepFake with Python  

**(You can access DeepFake implementation codes with Google Colab Link)**
https://colab.research.google.com/drive/1pjCcEmo9nGqH3ggSXwy6XgWXUJht06Ls?usp=sharing

## What is Deepfake? How does it operate?

Deepfake is a form of media in which a picture of one person is replaced with another using artificial neural
networks. The name "Deepfake" is derived from the underlying artificial intelligence (AI) technique known as "deep
learning." To create phony media that seems genuine, deep learning algorithms are utilized to swap faces in videos
and digital material. These algorithms train themselves to solve issues when given enormous amounts of data.

Although there are various ways to produce Deepfake media, the most popular one makes use of face-swapping
autoencoders in deep neural networks using autoencoders. To serve as the foundation for the Deepfake, a series of
video clips of the person you want to put in the target must come first, followed by a target video. The target video
may be a clip from a Hollywood film, for instance, while the films of the person you want to place in the movie could
be unrelated footage you acquired from YouTube.

A deep learning AI algorithm called the autoencoder is tasked with watching the video clips to learn how the
person appears from various perspectives and in various environments and then mapping that person onto the person
in the target video by identifying shared traits.

Generative Adversarial Networks (GANs), another kind of machine learning, are incorporated into the process.
GANs identify and fix any Deepfake problems over the course of several rounds, making it more challenging for
Deepfake detectors to identify them.

In order to "learn" how to create fresh instances that closely resemble the actual thing, GANs are also
frequently utilized as a popular technique for the production of DeepFake.


