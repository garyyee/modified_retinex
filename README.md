# Image Enhancement using Retinex-Net Algorithm with Attention Mechanisms

## ABSTRACT
<p align="justify">
This work introduces an improved version of Retinex-Net image enhancement algorithm, originally developed to enhance low-light images. The enhanced version incorporates the Mechanism-Decom and Mechanism-Enhance components from the original Retinex-Net which integrates Efficient Channel Attention Network (ECA-Net) and Deep Connected Attention Network (DCA-Net). This integration effectively reduces problems like irrelevant background distractions and local brightness inconsistencies, while improving the processing of image details and illumination. The three research objectives were to design the attention mechanism of Mechanism-Decom and Mechanism-Enhanced which are the subnetworks of the Retinex-Net algorithm, to analyze the effectiveness of incorporating an attention mechanism (ECA-Net and DCA-Net) into Retinex-Net algorithm and to evaluate the performance of tailored mechanisms using quantitative metrics. Modified Retinex-Net (ECA-Net + DCA-Net) demonstrated superior performance in terms of PSNR and SSIM from LOL dataset. When evaluating specific scene types, DCA-Net emerged as the top performer for NOL Dataset (Indoor scene), while ECA-Net excelled for NOL Dataset (Outdoor scene). The distinction between ECA-Net and DCA-Net performance in outdoor and indoor scenes underscores the importance of tailoring image enhancement techniques to specific environments. ECA-Net success in outdoor scenes and DCA-Net in indoor scenes suggest that different Retinex variants can be optimized for particular types of lighting and scene characteristics.</p><p align="center">


## Problem Statement
The existing Retinex-Net algorithm has been difficulty distinguishing between reflectance and illumination under intricate lighting scenarios, which can lead to incomplete enhancements. When the illumination map is intensified, noise is also magnified, causing a loss of detail and a grainy look.  The Retinex-Net algorithm may also cause incorrect color alterations or distortions, especially in regions with minor color differences. 

## Objectives
1. To design the attention mechanism of Mechanism-Decom and Mechanism-Enhance.
2. To analyze the effectiveness of incorporating an attention mechanism into Retinex-Net algorithm.
3. To compare the performance of tailored mechanisms using quantitative metrics 
