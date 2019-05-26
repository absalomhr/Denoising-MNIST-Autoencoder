# Denoising Autoencoder: MNIST Numbers
Given some images of numbers from the toy data set MNIST we apply some noise to them, and then using convolutional layers, max pooling layers and convolutional transpose layers try to de-noise the given images.
![GitHub Logo](/assets/autoencoder_denoise)
## Setup:
1. Create a conda environment:
Make sure you have installed: numpy matplotlib pandas jupyter notebook
```
conda create --name deep-learning python=3
conda install numpy matplotlib pandas jupyter notebook
```

2. Activate your environment:
* Windows:
```
activate deep-learning
```
* Mac/Linux:
```
source activate deep-learning
```

3. Run the notebook server in the root directory of the project:
```
jupyter notebook
```
* The server is located in: [localhost:8888](localhost:8888/tree)
4. Open the Jupyter notebook called: [Denoising_Autoencoder.ipynb](/Denoising_Autoencoder.ipynb)
## Results to expect:
### After training for 30 epochs and with a noise factor of: 0.5 we get the folowing training loss:
```
Epoch: 1    Training Loss: 0.280982
Epoch: 2    Training Loss: 0.271820
Epoch: 3    Training Loss: 0.267068
Epoch: 4    Training Loss: 0.262049
Epoch: 5    Training Loss: 0.258847
Epoch: 6    Training Loss: 0.255493
Epoch: 7    Training Loss: 0.253014
Epoch: 8    Training Loss: 0.251211
Epoch: 9    Training Loss: 0.249030
Epoch: 10   Training Loss: 0.248301
Epoch: 11   Training Loss: 0.246727
Epoch: 12   Training Loss: 0.246388
Epoch: 13   Training Loss: 0.245599
Epoch: 14   Training Loss: 0.245135
Epoch: 15   Training Loss: 0.244374
Epoch: 16   Training Loss: 0.244125
Epoch: 17   Training Loss: 0.243295
Epoch: 18   Training Loss: 0.243639
Epoch: 19   Training Loss: 0.243200
Epoch: 20   Training Loss: 0.242665
Epoch: 21   Training Loss: 0.242405
Epoch: 22   Training Loss: 0.241581
Epoch: 23   Training Loss: 0.242066
Epoch: 24   Training Loss: 0.241791
Epoch: 25   Training Loss: 0.241704
Epoch: 26   Training Loss: 0.241370
Epoch: 27   Training Loss: 0.240948
Epoch: 28   Training Loss: 0.240917
Epoch: 29   Training Loss: 0.240266
Epoch: 30   Training Loss: 0.240533
```
And the de-noised images look like this:
![GitHub Logo](/assets/noisy1.png)
## Conclusions
Some numbers may look better than other specially those with a shape with curves.