# Machines-Can-Draw-Neural-Style-Transfer

Hi Folks, welcome to this repositiry on neural style transfer, this is the implementation og gatys paper of 2015. The coherent idea here is to basically create a network which can be freezed by its trained weights over imagenet or pascal, and then optimize the input images from noise to fit content and stylise it. 
A few important underatnding and assumptions in this regard are:
1. Rather than starting from niose, I have selected a replica of starting image to start of
2. alpha is taken at 1 and beta at 0.01 which is different from the actual paper
3. The loss function is slightly modified to fit well.
4. Generall 6000-12000 epochs are trained for each sample of two images.
5. I donot have gpu so it was trained on kaggle and other open source libraries. 
6. The use of jupyter file is to elaborate learning and understanding internally than a package of complete work.

If you like my work please upvote this <a href="https://www.kaggle.com/tathagatbanerjee/machines-can-draw-neural-style-transfer-pytorch"> Notebook </a>

# Experiment 1

## Content
<img src="https://github.com/fsrt16/Machines-Can-Draw-Neural-Style-Transfer/blob/main/Data/Output/exp2_c.png" width="500">

## Style
<img src="https://github.com/fsrt16/Machines-Can-Draw-Neural-Style-Transfer/blob/main/Data/Output/exp2_s.png" width="500">

## Output
<img src="https://github.com/fsrt16/Machines-Can-Draw-Neural-Style-Transfer/blob/main/Data/Output/exp2_o.png" width="500">





# Experiment 2

## Content
<img src="https://github.com/fsrt16/Machines-Can-Draw-Neural-Style-Transfer/blob/main/Data/Output/exp5_c.png" width="500">

## Style
<img src="https://github.com/fsrt16/Machines-Can-Draw-Neural-Style-Transfer/blob/main/Data/Output/ep5_s.png" width="500">

## Output
<img src="https://github.com/fsrt16/Machines-Can-Draw-Neural-Style-Transfer/blob/main/Data/Output/exp5_o.png" width="500">



# More Results


<img src="https://github.com/fsrt16/Machines-Can-Draw-Neural-Style-Transfer/blob/main/Data/Output/exp4_o.png" width="500">

<img src="https://github.com/fsrt16/Machines-Can-Draw-Neural-Style-Transfer/blob/main/Data/Output/exp3_o.png" width="500">

<img src="https://github.com/fsrt16/Machines-Can-Draw-Neural-Style-Transfer/blob/main/Data/Output/exp2_o.png" width="500">

<img src="https://github.com/fsrt16/Machines-Can-Draw-Neural-Style-Transfer/blob/main/Data/Output/exp5_o.png" width="500">




