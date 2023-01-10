# Cross_Modal_Retrieval

| Image Dataset | Num       | Video Dataset | Num |
| ------------- | --------- | ------------- | --- |
| COCO          | 123K      | Flickr        | 31K |
|SBU            |           | VG            |  -  | 
|  CC3M         | 3.3M      | CUB           | 11K | 
|    Multi30K   | 151K      | CC14M         | 14M | 
| Fashion-Gen   | -         | XTD           | 10K | 
| Amazon reviews|    14M    |        -      |  -  |



| Video Dataset| Num | Video Dataset |Num|
|  ----------- | --------- | ------------ | --- |
| MSRVTT       |  10K      |MSVD          |     |
| LSMDC        |           |DIDEMO        |     |
| YouCook2     |           |YFCC          |     |
| CrossTask    |           |HowTo100M     |     |
| VaTeX        |           |Mining Youtube|     |
| WebVid2M     |           |QueryYD       |     |
|  VGGSound    | 14M       | LiveBot      |     |
|  Kinetics-700| 14M       | FCVID        | 91K |
|  ActivityNet | 20K       |              |     |



### 2022

|Task           |   Paper    |Dataset|Pretraining|Year|
|-----------    | --------- |-------|--------------|----|
|Image Retrieval|Multi-Lingual Acquisition on Multimodal Pre-training<br> for Cross-modal Retrieval [\[link\]](https://openreview.net/pdf?id=h73nTbImOt9) |CC3M, Multi30K, COCO, XTD, MSRVTT|Yes|2022|
|Video Retrieval|Text-Adaptive Multiple Visual Prototype Matching for<br> Video-Text Retrieval[\[link\]](https://openreview.net/pdf?id=XevwsaZ-4z)|MSRVTT, MSVD, DIDEMO, LSMDC|No|2022|
|Video Retrieval|Everything at Once – Multi-modal Fusion Transformer for Video Retrieval [\[link\]](https://openaccess.thecvf.com/content/CVPR2022/papers/Shvetsova_Everything_at_Once_-_Multi-Modal_Fusion_Transformer_for_Video_Retrieval_CVPR_2022_paper.pdf)|HowTo100M, Web, CrossTask, Mining YouTube|Yes|2022|
||**Cross Modal Retrieval with Querybank Normalisation** [\[link\]](https://openaccess.thecvf.com/content/CVPR2022/papers/Bogolin_Cross_Modal_Retrieval_With_Querybank_Normalisation_CVPR_2022_paper.pdf)|MSRVTT, LSMDC, MSVD, VaTeX,  QueryYD, DiDeMo|||
||**A Differentiable Semantic Metric Approximation in Probabilistic Embedding for Cross-Modal Retrieval** [\[link\]](https://openreview.net/pdf?id=-KPNRZ8i0ag)|COCO, CUB, Flickr|||
||EI-CLIP: Entity-aware Interventional Contrastive Learning for E-commerce Cross-modal Retrieval [\[link\]](https://openaccess.thecvf.com/content/CVPR2022/papers/Ma_EI-CLIP_Entity-Aware_Interventional_Contrastive_Learning_for_E-Commerce_Cross-Modal_Retrieval_CVPR_2022_paper.pdf)|Fashion-Gen, Amazon reviews|||
||COTS: Collaborative Two-Stream Vision-Language Pre-Training Model for Cross-Modal Retrieval [\[link\]](https://openaccess.thecvf.com/content/CVPR2022/papers/Lu_COTS_Collaborative_Two-Stream_Vision-Language_Pre-Training_Model_for_Cross-Modal_Retrieval_CVPR_2022_paper.pdf)|CC3M, CC14M, SBU, VG, COCO, Flickr|||
||ViSTA: Vision and Scene Text Aggregation for Cross-Modal Retrieval [\[link\]](https://openaccess.thecvf.com/content/CVPR2022/papers/Cheng_ViSTA_Vision_and_Scene_Text_Aggregation_for_Cross-Modal_Retrieval_CVPR_2022_paper.pdf)|VG, Flickr, TC, CTC|||
||**X-Pool: Cross-Modal Language-Video Attention for Text-Video Retrieval** [\[link\]](https://openaccess.thecvf.com/content/CVPR2022/papers/Gorti_X-Pool_Cross-Modal_Language-Video_Attention_for_Text-Video_Retrieval_CVPR_2022_paper.pdf) |\[MSVD, LSMDC, MSRVTT\]|||
||ECLIPSE: Efficient Long-range Video Retrieval using Sight and Sound [\[link\]](https://arxiv.org/pdf/2204.02874)| \[WebVid2M, VGGSound\]|||
||VTC: Improving Video-Text Retrieval with User Comments [\[link\]](https://arxiv.org/pdf/2210.10820)| \[LiveBot, Kinetics-700\]|||
||**Dual-Stream Knowledge-Preserving Hashing for Unsupervised Video Retrieval** [\[link\]](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136740175.pdf)| \[FCVID, ActivityNet and YFCC\]|||
||MILES: Visual BERT Pre-training with Injected Language Semantics for Video-text Retrieval [\[link\]](https://arxiv.org/pdf/2204.12408)| \[ CC3M, WebVid-2M, MSVD, LSMDC, DiDeMo\]|||
||**Multi-Query Video Retrieval** [\[link\]](https://arxiv.org/pdf/2201.03639)| \[MSR-VTT, MSVD, VATEX\]|||
||**Selective Query-guided Debiasing for Video Corpus Moment Retrieval** [\[link\]](https://arxiv.org/pdf/2210.08714)| \[TVR, ActivityNet, DiDeMo\]|||
||**TS2-Net: Token Shift and Selection Transformer for Text-Video Retrieval** [\[link\]](https://arxiv.org/pdf/2207.07852)| \[MSRVTT, VATEX, LSMDC, ActivityNet, DiDeMo\]|||
||**Learning Linguistic Association Towards Efficient Text-Video Retrieval** [\[link\]](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136960251.pdf)| \[MSRVTT, MSVD, VATEX\]|||
||**CODER: Coupled Diversity-Sensitive Momentum Contrastive Learning for Image-Text Retrieval** [\[link\]](https://arxiv.org/pdf/2208.09843)| \[COCO, Flickr\]|||
||Retrieve Fast, Rerank Smart: Cooperative and Joint Approaches for Improved Cross-Modal Retrieval [\[link\]](https://arxiv.org/pdf/2103.11920.pdf)| \[COCO, Flickr, CC14K\]|||
||Learning with Noisy Correspondence for Cross-modal Matching [\[link\]](https://openreview.net/pdf?id=S9ZyhWC17wJ)| \[COCO, Flickr, CC152K\]|||
|Image Retrieval|**Probabilistic Embeddings for Cross-Modal Retrieval** [\[link\]](https://openaccess.thecvf.com/content/CVPR2021/papers/Chun_Probabilistic_Embeddings_for_Cross-Modal_Retrieval_CVPR_2021_paper.pdf)| \[COCO, CUB\]|No|2021|
|Video Retrieval|TEACHTEXT: CrossModal Generalized Distillation for Text-Video Retrieval [\[link\]](http://www.csyangliu.com/Material/ICCV_TEACHTEXT.pdf)|MSRVTT|No|2021|
|Video Retrieval|**Adaptive Cross-Modal Prototypes for Cross-Domain Visual-Language Retrieval** [\[link\]](https://openaccess.thecvf.com/content/CVPR2021/papers/Liu_Adaptive_Cross-Modal_Prototypes_for_Cross-Domain_Visual-Language_Retrieval_CVPR_2021_paper.pdf)| \[COCO, MSRVTT, MSVD, LSMDC\]|No|2021|
|Image Retrieval|Learning Cross-Modal Retrieval with Noisy Labels [\[link\]](https://openaccess.thecvf.com/content/CVPR2021/papers/Hu_Learning_Cross-Modal_Retrieval_With_Noisy_Labels_CVPR_2021_paper.pdf)| Wikipedia, INRIA-Websearch, NUS-WIDE, XMediaNet|Yes|2021|
|Image Retrieval|Revamping Cross-Modal Recipe Retrieval with Hierarchical Transformers and Self-supervised Learning [\[link\]](https://openaccess.thecvf.com/content/CVPR2021/papers/Salvador_Revamping_Cross-Modal_Recipe_Retrieval_With_Hierarchical_Transformers_and_Self-Supervised_Learning_CVPR_2021_paper.pdf)| Recipe1M|Yes|2021|
|Image Retrieval|**Ask&Confirm: Active Detail Enriching for Cross-Modal Retrieval with Partial Query** [\[link\]](https://openaccess.thecvf.com/content/ICCV2021/papers/Cai_AskConfirm_Active_Detail_Enriching_for_Cross-Modal_Retrieval_With_Partial_Query_ICCV_2021_paper.pdf)| VG|No|2021|
|Image Retrieval|Product1M: Towards Weakly Supervised Instance-Level Product Retrieval via Cross-Modal Pretraining [\[link\]](https://openaccess.thecvf.com/content/ICCV2021/papers/Zhan_Product1M_Towards_Weakly_Supervised_Instance-Level_Product_Retrieval_via_Cross-Modal_Pretraining_ICCV_2021_paper.pdf)| \[Product1M\]|Yes|2021|
|Image Retrieval|**Wasserstein Coupled Graph Learning for Cross-Modal Retrieval** [\[link\]](https://openaccess.thecvf.com/content/ICCV2021/papers/Wang_Wasserstein_Coupled_Graph_Learning_for_Cross-Modal_Retrieval_ICCV_2021_paper.pdf)| Fickr, COCO, Real World Scene Graph, Moviegraphs|No|2021|
|Image Retrieval|Deep Hash Distillation for Image Retrieval [\[link\]](https://arxiv.org/pdf/2112.08816)| ImageNet, NUS-WIDE, COCO|Yes|2021|
|Video Retrieval|**Lightweight Attentional Feature Fusion: A New Baseline for Text-to-Video Retrieval** [\[link\]](https://arxiv.org/pdf/2112.01832)| \[MSRVTT, TGIF, MSVD, VATEX\]|No|2021|
|Video Retrieval|CodeCMR: Cross-Modal Retrieval For Function-Level Binary Source Code Matching [\[link\]](https://proceedings.neurips.cc/paper/2020/file/285f89b802bcb2651801455c86d78f2a-Paper.pdf)| YouCook2, MSRVTT, HowTo100M, CrossTask, Mining Youtube|Yes|2020|
|Image Retrieval|**IMRAM: Iterative Matching with Recurrent Attention Memory for Cross-Modal Image-Text Retrieval** [\[link\]](https://openaccess.thecvf.com/content_CVPR_2020/papers/Chen_IMRAM_Iterative_Matching_With_Recurrent_Attention_Memory_for_Cross-Modal_Image-Text_CVPR_2020_paper.pdf)| KWAI-AD, Flickr, COCO|No|2020|
|Video Retrieval|**Multi-modal Transformer for Video Retrieval** [\[link\]](https://arxiv.org/pdf/2007.10639)| \[MSRVTT, ActivityNet, LSMDC\]|No|2020|
|Image Retrieval|Preserving Semantic Neighborhoods for Robust Cross-modal Retrieval [\[link\]](https://arxiv.org/pdf/2007.08617)| Politics,  GoodNews, CC, COCO|Yes|2020|
|Image Retrieval|Learning Joint Visual Semantic Matching Embeddings for Language-guided Retrieval [\[link\]](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123670137.pdf)|Fashion200k|Yes|2020|
