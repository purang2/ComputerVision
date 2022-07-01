# Diffusion-based Image Generation

### DPM

최초의 Diffusion mechanism 

2015

### DDPM

DPM을 기반으로 여러가지 근간 메소드들을 정립함 

Jascha Sohl-Dickstein, Eric Weiss, Niru Maheswaranathan,
and Surya Ganguli. Deep unsupervised learning using
nonequilibrium thermodynamics. In International Conference on Machine Learning, pages 2256–2265. PMLR, 2015

Jonathan Ho, Ajay Jain, and Pieter Abbeel. Denoising diffusion probabilistic models. arXiv preprint arXiv:2006.11239,
2020.



### DDIM

DDPM의 Markovian을 Non-Markovian으로 define하여 training time을 매우 빠르게 (10~50배) 가능케 한 매우 중요한 방식 

Non-Markovian Process를 주목

더이상 확률모델이 아닌 묵시적 확률모델(implicit)이 되므로 DDIM이라 부른다

Jiaming Song, Chenlin Meng, and Stefano Ermon. Denoising
diffusion implicit models. arXiv preprint arXiv:2010.02502,
2020.
