# Neural_Artistic_Style

This project experiments with the Torch implementation of ["An Algorithm for Neural Style"](https://github.com/jcjohnson/neural-style) which is a Torch implementation of the following paper https://arxiv.org/abs/1508.06576

# Results

There were 9 images of varying image combination intensity. I've posted a couple below.

![demo image](https://github.com/honeyimholm/Neural_Artistic_Style/blob/master/out_900.png)
![demo image](https://github.com/honeyimholm/Neural_Artistic_Style/blob/master/out_300.png)
![demo image](https://github.com/honeyimholm/Neural_Artistic_Style/blob/master/out_100.png)

Original Uncombined Images:
![demo image](https://github.com/honeyimholm/Neural_Artistic_Style/blob/master/ME.jpg)
![demo image](https://github.com/honeyimholm/Neural_Artistic_Style/blob/master/starry_night.jpg)

# Notes

I ran this on a computer with a GTX 770 so I expected a pretty good run time. I had to run it in a VirtualBox Ubuntu environment because Windows does not support Torch. It turns out that VirtualBox does not have access to your GPU so this ended up taking 8 days to run...

# Next Steps
Next step is definitely to partition my hard drive so I can utilize my graphics card.

After that I'd like to explore if this stylistic image combination technique can be applied frame by frame to a movie like this person has done with Google Deep Dream and a scene from "Fear and Loathing In Las Vegas"

[Deep Dreaming Fear & Loathing in Las Vegas: the Great San Francisco Acid Wave](https://www.youtube.com/watch?v=oyxSerkkP4o)
