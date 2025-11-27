# SpatMoE: Spatially Adaptive Pixel-Level Mixture-of-Experts for Image Restoration
Xinyue Su, Yonghong Song, Yong Yu

<blockquote style="background:#f7f7f7; padding:15px; border-left:4px solid #cccccc;">
<div style="border:1px solid #d0d7de; background:#f6f8fa; padding:16px; border-radius:6px;">

<b>Abstract:</b> Real-world images often contain mixed and spatially uneven degradations such as noise, blur, and haze, where different regions require conflicting processing. Existing all-in-one models typically apply spatially shared operations and struggle to adapt to such heterogeneity. This paper presents SpatMoE, a spatially adaptive mixture-of-experts (MoE) that performs dense per-location fusion of three scale-specialized experts targeting local detail, mid-range structure, and global spectral correction. To enable adaptive fusion with minimal cost, we introduce Spatial Confidence Routing (SCR), a two-stage mechanism that forms a content-adaptive global prior and then refines fine-grained confidences to produce normalized fusion weights in a single pass. Unlike conventional MoE architectures that route at image or patch granularity, SpatMoE adapts within the image and allocates capacity exactly where it is most needed. Extensive experiments across diverse image restoration tasks demonstrate the effectiveness and scalability of our method.

</div>


# Network Architecture
![architecture](https://raw.githubusercontent.com/emma-sue/SpatMoE/main/architecture.jpg)
