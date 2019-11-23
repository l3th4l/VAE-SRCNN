# VAE-SRCNN
results of training SRCNN Image Super-Resolution network on a VAE's output

## VAE 

![output](https://github.com/l3th4l/VAE-SRCNN/blob/master/gifs/ezgif-2-48c8fa9858c5.gif)

*left* : Reconstructed Output , *right* : Ground Truth

### Latent Space Interpolation 
![latent](https://github.com/l3th4l/VAE-SRCNN/blob/master/gifs/ezgif.com-gif-maker_r.gif)

### SRCNN on VAE output 
![srcnn](https://github.com/l3th4l/VAE-SRCNN/blob/master/gifs/ezgif-2-f32a39f57016.gif) 

*left* : VAE Output , *right* : Result on applying SRCNN on VAE output 

**P.S. Didn't go quiet as expected. The results turned out to be more blurry than the VAE output but it eleminated some of the 
noise and was better in some cases like the one below:**

#### Ground Truth :
![gt](https://media.discordapp.net/attachments/542340298408198145/647754592964182028/wH3GV2UoqFxowAAAABJRU5ErkJggg.png?width=229&height=227)
#### VAE :
![ae](https://media.discordapp.net/attachments/542340298408198145/647754549137899532/BlAH8G355p4Y9MvciIrYQkbkXEbGFiDdRMQWIt74ERFbiHjjR0RsIeKNHxGxhYg3fkTEFiLeBERW4h440dEbCHD2gOTtFKULD0AA.png?width=229&height=227)
#### SRCNN on VAE output :
![sr](https://media.discordapp.net/attachments/542340298408198145/647754566938394672/KcGu7KbeC7MAAAAASUVORK5CYII.png?width=229&height=227)
