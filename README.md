# Calculating Fisher ratio in the CNN latent representation
2d t-SNE/Latent discriminant analysis (LDA) embedding of the latent representation in the fully connected layer in CNN trained using MNIST digit dataset. CNN was trained from random initialization and gradually the internal representation has a specific feature for each digit images.

Fisher ratio: https://en.wikipedia.org/wiki/Linear_discriminant_analysis

Fisher ratio in a DNN work: https://arxiv.org/pdf/2012.10424.pdf

## t-SNE embedding of the CNN hidden representation
![movie_tsne](https://user-images.githubusercontent.com/1684732/151492801-8ee759d9-ab92-4a1e-8b13-2d7b05e5b501.gif)

## LDA embedding of the CNN hidden representation
![movie](https://user-images.githubusercontent.com/1684732/151492496-151e9e1d-4442-4299-8ade-32d6f9e42305.gif)

# Trace of Fisher ratio
Trace of the Fisher ratio $Tr(inv(within-class_covariance) * between-class_covariance) / n_class$ can quantitively measure the distribution of distributions with class labels.  

## Various number of classes and variance
![movie_fisher2](https://user-images.githubusercontent.com/1684732/151509620-29e52e4c-dfb3-43fa-9a82-6ca9b80fd3fd.gif)
![movie_fisher4](https://user-images.githubusercontent.com/1684732/151509629-9c6da500-3910-4632-bd47-758ad2c81734.gif)

## Various positions of class means
![movie_fisher4_mean](https://user-images.githubusercontent.com/1684732/151520028-75c5a37e-c8d6-44b4-8217-6d7c3b691973.gif)
