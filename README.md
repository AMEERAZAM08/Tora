<div align="center">
<h2><center>Tora: Trajectory-oriented Diffusion Transformer for Video Generation</h2>

Zhenghao Zhang\*,  Junchao Liao\*, Menghao Li, Long Qin, Weizhi Wang

\* equal contribution

<a href='https://arxiv.org/abs/2407.21705'><img src='https://img.shields.io/badge/ArXiv-2407.21705-red'></a> 
<a href='https://ali-videoai.github.io/tora_video/'><img src='https://img.shields.io/badge/Project-Page-Blue'></a>  ![views](https://visitor-badge.laobi.icu/badge?page_id=ali-videoai.Tora&left_color=gray&right_color=green)
</div>

## Abstract
Recent advancements in Diffusion Transformer (DiT) have demonstrated remarkable proficiency in producing high-quality video content. Nonetheless, the potential of transformer-based diffusion models for effectively generating videos with controllable motion remains an area of limited exploration. This paper introduces Tora, the first trajectory-oriented DiT framework that integrates textual, visual, and trajectory conditions concurrently for video generation. Specifically, Tora consists of a Trajectory Extractor (TE), a Spatial-Temporal DiT, and a Motion-guidance Fuser (MGF). The TE encodes arbitrary trajectories into hierarchical spacetime motion patches with a 3D video compression network. The MGF integrates the motion patches into the DiT blocks to generate consistent videos following trajectories. Our design aligns seamlessly with DiT’s scalability, allowing precise control of video content’s dynamics with diverse durations, aspect ratios, and resolutions. Extensive experiments demonstrate Tora’s excellence in achieving high motion fidelity, while also meticulously simulating the movement of physical world.

## Showcases

https://github.com/user-attachments/assets/44eef320-c8a0-49e2-a272-a403ac8cb530

https://github.com/user-attachments/assets/c1c9a818-ef29-498f-b730-de39376c61a4

## TODO List
- [ ] Hugging Face Demo.
- [ ] Release our inference code.
- [ ] Release our training code.

## Citation
```bibtex
@misc{tora,
      title={Tora: Trajectory-oriented Diffusion Transformer for Video Generation}, 
      author={Zhenghao Zhang and Junchao Liao and Menghao Li and Long Qin and Weizhi Wang},
      year={2024},
      eprint={2407.21705},
      archivePrefix={arXiv},
      primaryClass={cs.CV},
      url={https://arxiv.org/abs/2407.21705}, 
}
```
