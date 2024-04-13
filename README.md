# VAE
VAE
there are two notes:
in loss, we say we want the distribution to be like a normal distribution so KL of (encoder, normal)=0.
instead of directly sampling from a distribution with mean and std of encoder we randomly get a sample from a normal distribution and * std + mean so it is the same as sampling from a distribution with mean and variance. 
