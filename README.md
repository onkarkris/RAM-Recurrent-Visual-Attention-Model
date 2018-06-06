# RAM
Recurrent Attention Model 
code: 'ram_modified.py'

# Description
This project is modification of https://github.com/jtkim-kaist/ram_modified. The problem with the last implementation was in loss function  of the activation network. In the modified version we have used cross entropy loss on the output of activation network. Only this small changed speed up the convergence. The previous version reported the result that "after 600,000 epoch, I got about 98% accuracy".

# Result 
Only after 90,000 epoch, I have got the same accuracy. 
