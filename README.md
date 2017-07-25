# pix2pix-keras
Pix2pix implementation in keras. 
Forked from williamfalcon's one.

Original paper: [Image-to-Image Translation with Conditional Adversarial Networks (pix2pix)](https://arxiv.org/pdf/1611.07004.pdf)    
Paper Authors and Researchers: Phillip Isola, Jun-Yan Zhu, Tinghui Zhou, Alexei A. Efros    

### Changed Point (Kajiyu)
- Optimized to python2.7 and keras2.0.
- Enabled to use keras-gpu in Ubuntu16.04.
- Used tensorflow instead of theano, for backend.

### To run    
```bash
# clone repo and step into root dir
git clone https://github.com/williamFalcon/pix2pix-keras.git
cd pix2pix-keras/pix2pix

# download facades dataset   
python utils/facades_dataset.py

# setup conda(or virtual env)
conda create -n pix python=2.7  
source activate pix

# install requirements
pip install requirements.txt

# start training
python main.py 
```    

### About this implementation  
A full write-up about this implementation is available at my blog [https://www.williamfalcon.com/deeplearningimplementations/pix2pix-keras](https://www.williamfalcon.com/deeplearningimplementations/pix2pix-keras)
