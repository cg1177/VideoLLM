# VideoLLM
Preprint: [VideoLLM: Modeling Video Sequence with Large Language Models](https://arxiv.org/abs/2305.13292)



With the exponential growth of video data, there is an urgent need for automated technology to analyze and comprehend video content. However, existing video understanding models are often task-specific and lack a comprehensive capability of handling diverse tasks.
The success of large language models (LLMs) like GPT has demonstrated their impressive abilities in sequence causal reasoning. Building upon this insight, we propose a novel framework called $\texttt{\textbf{VideoLLM}}$ that leverages the sequence reasoning capabilities of pre-trained LLMs from natural language processing (NLP) for video sequence understanding.
$\texttt{\textbf{VideoLLM}}$ incorporates a carefully designed Modality Encoder and Semantic Translator, which convert inputs from various modalities into a unified token sequence. This token sequence is then fed into a decoder-only LLM. Subsequently, with the aid of a simple task head, our $\texttt{\textbf{VideoLLM}}$ yields an effective unified framework for different kinds of video understanding tasks.
To evaluate the efficacy of $\texttt{\textbf{VideoLLM}}$, we conduct extensive experiments using multiple LLMs and fine-tuning methods. We evaluate our $\texttt{\textbf{VideoLLM}}$ on eight tasks sourced from four different datasets. The experimental results demonstrate that the understanding and reasoning capabilities of LLMs can be effectively transferred to video understanding tasks.

## 🏠 Overview
![intro_white_cut](https://github.com/cg1177/VideoLLM/assets/95628472/5bcc0dbc-254d-4bf9-b884-b7034a6e0286)


## 🎫 License

This project is released under the [Apache 2.0 license](LICENSE). 


## 🖊️ Citation

If you find this project useful in your research, please consider cite:

```BibTeX
@misc{2023videollm,
    title={VideoLLM: Modeling Video Sequence with Large Language Models},
    author={Guo Chen, Yin-Dong Zheng, Jiahao Wang, Jilan Xu, Yifei Huang, Junting Pan, Yi Wang, Yali Wang, Yu Qiao, Tong Lu and Limin Wang},
    howpublished = {\url{https://arxiv.org/abs/2305.13292)},
    year={2023}
}
```
