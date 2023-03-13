# VGAE-MCTS
VGAEはkGCNで用意されているモデルを使用する。
(URL: https://github.com/clinfo/kGCN/tree/master/sample_chem/generative_model )  
MCTSは別のレポジトリーにあるモデルを使用する。 
(URL: https://github.com/clinfo/GraphGenerativeModel/tree/nakai_ver )  

# VGAEについて
VGAEのモデルは、https://github.com/clinfo/kGCN/tree/master/example_model 内のmodel_vae.pyとmodel_vae_gen.pyを使用する。  
model_vae.pyはVGAEの訓練及び再構成時に使用し、model_vae_gen.pyは生成時に使用する。  

# VGAEの学習データセットについて
sample_dataのディレクトリ内にGuacaMolのベンチマーク測定の際に使用したChEMBLのデータセットと物性値最適化の際に使用したZINCのデータセットを用意している。
