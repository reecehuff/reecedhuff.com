---
title: "Machine learning for _in vivo_ strain prediction"
excerpt: "How can we learn to predict strain _in vivo_ using state-of-the-art machine learning techniques in combination with medical imaging? <br/><img src='/images/StrainNet.gif' alt='StrainNet' width='600'/>"
collection: portfolio
---

Measuring _in vivo_ strain is challenging. Previously, researchers have measured strain _in vivo_ by combining medical imaging with classical image texture correlation algorithms, e.g., direct deformation estimation (DDE) and digital image correlation (DIC). However, these techniques are often limited by low signal-to-noise ratios, poor image texture, and other image artifacts. Thus, our lab has developed a deep convolutional neural network, StrainNet, to automatically measure patient-specific in vivo strains from high-frequency ultrasound images (Fig. 2A). Applying StrainNet on ultrasound images of human flexor tendons (Fig. 2B), we have been able automatically segment the tendon as well as accurately capture strain distributions (Fig. 2C) by passing image sequences through a deep convolutional neural network (Fig. 2D). Currently, StrainNet has demonstrated a greatly improved predictive power with a mean strain error 90% lower than DDE and DIC (Fig. 2E). We believe StrainNet will generalize to other biological domains beyond soft tissues as we aim to uncover in vivo tissue behavior under loading, in order to better understand tissue injury and rehabilitation mechanisms.

<figure><img src="/images/StrainNet.gif" alt="StrainNet_gif"><figcaption align = "center"><b>Figure 1:</b> Conceptual view of StrainNet</figcaption></figure>

<figure><img src="/images/StrainNet.png" alt="StrainNet"><figcaption align = "center"><b>Figure 2:</b> (A) Grip testing setup for flexor tendon contraction. (B) Representative tendon ultrasound image. (C) The applied strain field and the strain field predicted by StrainNet. (D) StrainNet architecture: A full strain field is predicted from a pair of ultrasound images. (E) Mean strain error from StrainNet compared to traditional image correlation techniques (DDE and DIC).</figcaption></figure>
