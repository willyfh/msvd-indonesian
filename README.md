# MSVD-Indonesian
MSVD-Indonesian is derived from the MSVD dataset, which is obtained with the help of a machine translation service. This dataset can be used for multimodal video-text tasks, including text-to-video retrieval, video-to-text retrieval, and video captioning. Same as the original English dataset, the MSVD-Indonesian dataset contains about 80k video-text pairs.

## Data

Indonesian sentences: [link](https://github.com/willyfh/msvd-indonesian/blob/main/data/MSVD-indonesian.txt)

Raw videos: [link](https://www.cs.utexas.edu/users/ml/clamp/videoDescription/YouTubeClips.tar)

## Qualitative Results

### Text-to-Video  Retrieval
![Text-to-Video Retrieval](figures/qualitative-results-t2v-ret.png)

### Video-to-Text Retrieval
![Video-to-Text Retrieval](figures/qualitative-results-v2t-ret.png)

### Video Captioning
![Video Captioning](figures/qualitative-results-v2t-cap.png)

## Citation
If you find our work useful in your research, please cite:

```bibtex
@article{Hendria2023MSVDID,
  title={{MSVD}-{I}ndonesian: A Benchmark for Multimodal Video-Text Tasks in Indonesian 	},
  author={Willy Fitra Hendria},
  journal={arXiv preprint arXiv:XXXXXXXXXX},
  year={2023}
}
```

## Acknowledgments
Our experimental results are obtained utilizing the resources from [X-CLIP](https://github.com/xuguohai/X-CLIP) and [VNS-GRU](https://github.com/WingsBrokenAngel/delving-deeper-into-the-decoder-for-video-captioning). We thank the original authors for their open-sourcing.
