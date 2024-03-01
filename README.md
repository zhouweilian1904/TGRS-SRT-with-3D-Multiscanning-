# TGRS-SRT-with-3D-Multiscanning
--------------------------------
Weilian Zhou, Sei-ichiro Kamata, Haipeng Wang, Pengfeng LU, Mengyunqiu Zhang

Feel free to contact us if there is anything we can help. Thanks for your support!

zhouweilian1904@akane.waseda.jp

--------------------------------
**The detailed structure of the proposed idea is shown below.**
![image](https://github.com/zhouweilian1904/TGRS-SRT-with-3D-Multiscanning-/blob/main/concept%204.png)

--------------------------------
**Abstract:**

This study introduces an innovative approach in
hyperspectral imaging (HSI) classification by integrating con-
volution, recurrence, and self-attention mechanisms in a 3D
configuration. We address several challenges such as the 1)
disruption of spectral continuity by traditional dimensionality
reduction methods like PCA, 2) the overlooking of band-to-band
continuous features in existing spatial-only 2D multiscanning
strategy, and 3) the limitations in model design by simply cascad-
ing recurrent neural networks (RNNs) with Transformers for HSI
analysis. Our solution involves three core components: 1) sub-
band grouping with group-wise convolution for refined dimension
reduction, 2) a novel cubed 3D-multiscanning technique enabling
thorough multi-directional analysis in both spectral and spatial
domains, and 3) the development of a Cubic-Net framework with
a specially designed Segmented Recurrent Transformer (SRT).
This SRT is tailored to effectively utilize spectral continuity along
with spatial contextual features, overcoming common sequen-
tial data analysis challenges seen in RNNs and Transformers.
Furthermore, our feature fusion strategy successively integrates
’short-term’ and ’long-term’ SRT features, thereby enhancing
the model’s ability to process both spectral and spatial features
effectively. Experimental results from three public HSI datasets
indicate our method’s improved performance over existing base-
lines and state-of-the-art methods. This research offers a new
perspective in 3D sequential HSI classification.
