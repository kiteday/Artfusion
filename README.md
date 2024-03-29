# [Artfusion: A Diffusion Model-Based Style Synthesis Framework for Portraits]([url](https://www.mdpi.com/2079-9292/13/3/509))
> Abstract
> We present a diffusion model-based approach that applies the artistic style of an artist or an art movement to a portrait photograph. Learning the style from the artworks of an artist or an art movement requires a training dataset composed of a lot of samples. We resolve this limitation by combining Contrastive Language Image Pretraining (CLIP) encoder and diffusion model, since the CLIP encoder extracts the features from an input portrait in a very effective way. Our framework includes three independent CLIP encoders that extract the text features, color features and Canny edge features from an input portrait, respectively. These features are incorporated to the style information extracted through a diffusion model to complete the stylization on an input portrait. The diffusion model extracts the style information from the sample images in the training dataset using an image encoder. The denoising steps in the diffusion model applies the style information from the training dataset to the CLIP-based features from an input portrait. Finally, our framework produces an artistic portrait that presents both the identity of the input portrait and the artistic style from the training dataset. The most important contribution of our framework is that our framework requires less than a hundred sample images for an artistic style. Therefore, our framework can successfully extract styles from an artist who has drawn less than a hundred artworks. We sample three artists and three art movements and apply these styles to the portraits of various identities and produce visually pleasing results. We evaluate our results using various metrics, including Frechet Inception Distance (FID), ArtFID and Language-Image Quality Evaluator (LIQE) to prove the excellence of our results.

![image](https://github.com/kiteday/Artffusion/assets/74218895/6af166d0-2d19-4767-8d93-209541059445)

# Citation
```
@article{yang2024artfusion,
  title={Artfusion: A Diffusion Model-Based Style Synthesis Framework for Portraits},
  author={Yang, Hyemin and Yang, Heekyung and Min, Kyungha},
  journal={Electronics},
  volume={13},
  number={3},
  pages={509},
  year={2024},
  publisher={MDPI}
}
```
