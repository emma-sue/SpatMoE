# SpatMoE: Spatially Adaptive Pixel-Level Mixture-of-Experts for Image Restoration
Xinyue Su (Graduate Student Member, IEEE), Yonghong Song (Member, IEEE), Yong Yu
<blockquote style="background:#f7f7f7; padding:15px; border-left:4px solid #cccccc;">
<b>Abstract:</b>  
Real-world images often contain mixed and spatially uneven degradations such as noise, blur, and haze, where different regions require conflicting processing. Existing all-in-one models typically apply spatially shared operations and struggle to adapt to such heterogeneity.
<br><br>
This paper presents <b>SpatMoE</b>, a spatially adaptive mixture-of-experts (MoE) that performs dense per-location fusion of three scale-specialized experts targeting local detail, mid-range structure, and global spectral correction.
<br><br>
To enable adaptive fusion with minimal cost, we introduce <b>Spatial Confidence Routing (SCR)</b>, a two-stage mechanism that forms a content-adaptive global prior and then refines fine-grained confidences to produce normalized fusion weights in a single pass. Unlike conventional MoE architectures that route at image or patch granularity, SpatMoE adapts within the image and allocates capacity exactly where it is most needed.
<br><br>
Extensive experiments across diverse image restoration tasks demonstrate the effectiveness and scalability of our method.
</blockquote>
# Network Architecture
![architecture](https://github.com/emma-sue/SpatMoE/blob/main/architecture.jpg)
