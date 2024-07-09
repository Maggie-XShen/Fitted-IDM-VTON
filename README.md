# IDM-VTON: Improving Diffusion Models for Authentic Virtual Try-on in the Wild</h1>
This modification of the official repo's gradio_demo/app.py allows running the model with
```
!python ./gradio_demo/app.py \
    --model_img ["model_image"] \
    --garm_img ["garment_image"] \
    --garment_des ["description"] \
    --[is_checked] \
    --[is_checked_crop] \
    --denoise_steps [denoise_steps] \
    --seed [seed]
```

# Colab Notebook
Instructions on how to run the modified inference code from gradio_demo/app.py can be found in the colab notebook.
The colab notebook can be found here: 
- https://colab.research.google.com/drive/1-9HiUxlTsbdMfIts90iVwKNNWYPHRW4i?usp=sharing

# Citation
```
@article{choi2024improving,
  title={Improving Diffusion Models for Virtual Try-on},
  author={Choi, Yisol and Kwak, Sangkyung and Lee, Kyungmin and Choi, Hyungwon and Shin, Jinwoo},
  journal={arXiv preprint arXiv:2403.05139},
  year={2024}
}
``
