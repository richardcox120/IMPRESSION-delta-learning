# &Delta;-learning with IMPRESSION
<p align="center">
<img src="https://pubs.rsc.org/en/Image/Get?imageInfo.ImageType=GA&imageInfo.ImageIdentifier.ManuscriptID=C9SC03854J&imageInfo.ImageIdentifier.Year=2020">
</p>

IMPRESSION (Intelligent Machine PREdiction of Shift and Scalar information Of Nuclei) is a graph transformer network predicts chemical shift and coupling constant from a 3D structure.

The architecture originally used by IMPRESSION was based on Kernel Ridge Regression classification. Previous work by Chapparova successfully proved that &Delta;-learning could be applied to IMPRESSION, and scaled up (relatively inaccurate) Density Functional Theory (DFT) NMR calculations with a small basis set (3-21G) to an equivalent of DFT NMR calculations with a larger basis set (6-311G).

This work expands this from 1<sup>st</sup> generation IMPRESSION (Kernel Ridge Regression) to 2<sup>nd</sup> generation IMPRESSION (graph transformer network).
Future work would involve the collection and processing of experimental data and attempting to have IMPRESSION predict experimental results, potentially leading to
