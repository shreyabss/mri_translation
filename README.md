****Cycle Generative Adversarial Networks for MRI Translation****

This project explores the use of Generative Adversarial Networks (GANs) for generating synthetic brain Magnetic Resonance Imaging (MRI) sequences. The focus is on transforming T1-weighted MRI images to T2-weighted images and vice versa, using a CycleGAN architecture. The synthetic images generated can be used for enhancing diagnostic reliability, physician training, and computer-aided diagnosis.

**Dataset**

MICCAI BRATS 2020: Contains MRI images of 335 patients with High-Grade Glioma (HGG) and Low-Grade Glioma (LGG) and CrossMoDA 2020: Includes MRI images of 242 patients with Vestibular-Schwannoma.

**Methodology**

Data Preprocessing: Slicing of MRI volumes and conversion to 2D axial slices.

CycleGAN Architecture: Utilizing two generators and two discriminators for domain translation between T1 and T2-weighted images.

Training: Employing adversarial and cycle-consistency losses for training the model.

**Results**

The trained CycleGAN model successfully transformed T1-weighted images to T2-weighted images and vice versa. The quality of the generated images was evaluated using PSNR, MSE, and SSIM metrics, showing promising results.
