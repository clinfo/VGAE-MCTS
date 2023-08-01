# VGAE-MCTS: a New Molecular Generative Model combining Variational Graph Auto-Encoder and Monte Carlo Tree Search

Authors: Hiroaki Iwata, Taichi Nakai, Takuto Koyama, Shigeyuki Matsumoto, **Ryosuke Kojima**, and **Yasushi Okuno**

VGAE uses a model provided in kGCN.
(URL: https://github.com/clinfo/kGCN/tree/master/sample_chem/generative_model )

MCTS uses a model located in a separate repository.
(URL: https://github.com/clinfo/GraphGenerativeModel/tree/nakai_ver )

# About VGAE
The VGAE model uses model_vae.py and model_vae_gen.py found within https://github.com/clinfo/kGCN/tree/master/example_model. model_vae.py is used for VGAE training and reconstruction, and model_vae_gen.py is used for generation.

# About VGAE's Training Dataset
Within the sample_data directory, datasets from ChEMBL used for GuacaMol benchmarking and from ZINC used for physical property optimization are prepared."
