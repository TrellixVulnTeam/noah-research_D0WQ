# Natural Language Processing (NLP)

This repository provides some of the NLP techniques developed by Huawei Noah's Ark Lab.

## Directory structure

* [FreeTransfer-X](https://github.com/huawei-noah/noah-research/tree/master/NLP/FreeTransfer-X) enables safe and label-free cross-lingual transfer from off-the-shelf models, which is published in [NAACL Findings 2022](https://arxiv.org/pdf/2206.06586.pdf).
* [XeroAlign](https://github.com/huawei-noah/noah-research/tree/master/xero_align) allows for efficient SOTA zero-shot cross-lingual transfer with machine translated pairs via a simple and lightweight auxiliary loss, originally published in [ACL Findings 2021](https://aclanthology.org/2021.findings-acl.32/).
* [CrossAligner](https://github.com/huawei-noah/noah-research/tree/master/NLP/cross_aligner) is an extension of XeroAlign (above) with a more effective NER (slot tagging) alignment based on machine translated pairs, new labels/objective derived from English labels and a SOTA weighted combination of losses. Additional analysis in the appendix, please read our [ACL Findings 2022](https://arxiv.org/abs/2203.09982v1) paper).
* [DyLex](https://github.com/huawei-noah/noah-research/tree/master/NLP/dylex)
* [UniMS](https://github.com/huawei-noah/noah-research/tree/master/NLP/UniMS) a unified multimodal summarization framework with an encoder-decoder multitask architecture
on top of BART, which simultaneously outputs extractive and abstractive summaries, and image selection results. Our framework adopts knowledge distillation to improve
image selection without any requirement on the existence and quality of image captions. We further introduce the extractive objective in the encoder and visual guided attention in the decoder to better integrate both textual and visual modalities in the conditional text generation. Our unified method achieves a new state-of-the-art result of multimodal summarization, and more details can be found in the [AAAI 2022](https://www.aaai.org/AAAI22Papers/AAAI-5436.ZhangZ.pdf) paper.
* [SumTitles](https://github.com/huawei-noah/noah-research/tree/master/SumTitles)
* [Conversation Graph](https://github.com/huawei-noah/noah-research/tree/master/conv_graph) allows for effective data augmentation, training loss 'augmentation' and a fairer evaluation of dialogue mamagement in a modular conversational agent. We introduce a novel idea of a convgraph to achieve all that. Read more in our [TACL 2021](https://direct.mit.edu/tacl/article/doi/10.1162/tacl_a_00352/97777/Conversation-Graph-Data-Augmentation-Training-and) paper.
* [FreeGBDT](https://github.com/huawei-noah/noah-research/tree/master/freegbdt) investigates whether it is feasible (or superior) to replace the conventional MLP classifier head used with pretrained transformers with a gradient-boosted decision tree. Want to know if it worked? Take a look at the [ACL Findings 2021](https://aclanthology.org/2021.findings-acl.26.pdf) paper!
* [Dual Transfer](https://github.com/huawei-noah/noah-research/tree/master/noahnmt/dual-transfer)
* [MultiUAT](https://github.com/huawei-noah/noah-research/tree/master/noahnmt/multiuat)
* [PERT](https://github.com/huawei-noah/noah-research/tree/master/noahime/PERT) is a transformer-based solution for pinyin-to-character conversion task which is core to the Chinese input method.
* [Maha_OOD](https://github.com/huawei-noah/noah-research/tree/master/Maha_OOD) is unsupervised method for out-of-domain detection for intents. The code to reproduce the results from the paper [AAAI 2021](https://arxiv.org/abs/2101.03778)
