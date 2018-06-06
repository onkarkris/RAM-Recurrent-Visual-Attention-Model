# RAM
Recurrent Attention Model 
# Code
code: 'ram_modified.py'
# Playing with loss function in RAM 
This project is a modified version of https://github.com/jtkim-kaist/ram_modified. The previous version reported about 98% accuracy 
after 600,000 epoch. In the modified RAM, I have changed the loss function from the activation network to cross entropy loss 
and achieved similar accuracy with much less epoch, around  90,000. In this code, you can play with code by changing the loss function 
to triplet or saeimes which are mainly used for training the image search engines.

# Reference
Recurrent Models of Visual Attention

http://papers.nips.cc/paper/5542-recurrent-models-of-visual-attention.pdf

https://arxiv.org/pdf/1412.7755.pdf
