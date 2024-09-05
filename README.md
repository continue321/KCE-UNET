## Abstract
During concerts, people often spontaneously record memorable moments with their phones. However, these recordings are frequently accompanied by noise, such as cheering and applause, which diminishes the playback experience. In this paper, we introduce a novel task specifically designed for denoising music in concert environments, a challenge that has been largely overlooked in previous research. To support this task, we created a new concert denoising dataset that includes songs performed in various major languages at concerts, accompanied by noise segments like cheering and applause. Building on this, we propose KANConv ECA Unet (KCE-Unet), a method that combines the U-Net network, Efficient Channel Attention (ECA), and the recently proposed KAN network to flexibly remove noise in the mid-to-high frequency range of spectrograms. Extensive experiments demonstrate that our method outperforms previous models in denoising performance and effectively restore disrupted musical structures.

<p align="center">
  <img src="images/KCE_Unet.png" alt="KCE-Unet Architecture" width="50%">
</p>

<p align="center"><b>Figure 1: KCE-Unet Architecture</b></p>

