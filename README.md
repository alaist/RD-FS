# Reinforced Disentanglement for Face Swapping without Skip Connection

Xiaohang Ren, Xingyu Chen, Pengfei Yao, Heung-Yeung Shum, and Baoyuan Wang.

### [Paper](https://arxiv.org/pdf/2307.07928) 

<img src='./images/title3.jpg' width=1000>

The SOTA face swap models still suffer the problem of either target identity (i.e., shape) being leaked or the target
non-identity attributes (i.e., background, hair) failing to be fully preserved in the final results. We show that this insufficient disentanglement is caused by two flawed designs that were commonly adopted in prior models: (1) counting on only one compressed encoder to represent both the semantic-level non-identity facial attributes(i.e., pose) and the pixel-level non-facial region details, which is contradictory to satisfy at the same time; (2) highly relying on long skip-connections between the encoder and the final generator, leaking a certain amount of target face identity into the result. To fix them, we introduce a new face swap framework called “WSC-swap” that gets rid of skip connections and uses two target encoders to respectively capture the pixel-level non-facial region attributes and the semantic non-identity attributes in the face region. To further reinforce the disentanglement learning for the target encoder, we employ both identity removal loss via adversarial training (i.e., GAN) and the non-identity preservation loss via prior 3DMM models like. Extensive experiments on both FaceForensics++ and CelebA-HQ show that our results significantly outperform previous works on a rich set of metrics, including one novel metric for measuring identity consistency that was completely neglected before.



## License and Citation

The usage of this software is under [CC-BY-4.0](https://github.com/alaist/RD-FS/LICENSE).
```
}
@inproceedings{ren2023reinforced,
  title={Reinforced Disentanglement for Face Swapping without Skip Connection},
  author={Ren, Xiaohang and Chen, Xingyu and Yao, Pengfei and Shum, Heung-Yeung and Wang, Baoyuan},
  journal={arXiv preprint arXiv:2307.07928},
  year={2023}
}

```

###  We will release our code and models in the near feature. Stay tuned.