# CLIP is all you need (c) [crumb](https://twitter.com/aicrumb)
Greatly inspired by [this tweet](https://twitter.com/aicrumb/status/1448351059957764096/photo/1) and all the CLIP guided approaches.

What if we directly optimize raw image tensor using CLIP, instead of tuning a generator network or its inputs? 
Just like style transfer algos were doing 5 years ago :D

This is a place for all my hacks on this topic. Feel free to open this [notebook in colab](https://colab.research.google.com/drive/1hw2A5WIE4KRfdLZ5PXeIKPLTkwfFtziS?usp=sharing) and mess around :D 

# TODO
- [ ] Add loss from VQGAN CLIP
- [ ] Add loss from CLIP guided diffusion
- [x] Embed cuts in a batch (x6 speedup)
- [x] Add tv_loss and range_loss
