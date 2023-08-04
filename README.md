<p align=center>
<h1 align=center>Awesome <img src="https://big-cheng.com/img/lclm.png" alt="covidia-logo" width="100"/> papers</h1>
<h4 align=center><em>Awesome Papers of Long Context Language Model</em></h4>
</p>

- Under Construction
- TODO
- [ ] Citation of each paper
- [ ] Link of each paper
- [ ] Survey paper
---
## Introduction (Draft by ChatGPT😄)

Traditional language models like [ChatGPT](https://chat.openai.com/) have a fixed context window, which means they can only consider a limited number of tokens (words or subwords) as input to generate the next word in a sequence. For example, the original GPT-3.5 has a maximum context window of **2,048** tokens. This limitation poses challenges when dealing with longer pieces of text, as it may cut off relevant information beyond the context window.

![Figure taken from Longformer](https://huggingface.co/blog/assets/14_long_range_transformers/Longformer.png)

To overcome this limitation and better model long-range dependencies in text, researchers have explored various techniques and architectures. The following are some approaches that might be considered as "long context language models".

## PaperList

### Survey

- Coming soon ...

### Model

#### Memory/Cache-Augmented Models
> Some language models incorporate external memory mechanisms, allowing them to store information from past tokens and retrieve it when necessary. These memories enable the model to maintain context over longer segments of text.

- Dual Cache for Long Document Neural Coreference Resolution
- XMem: Long-Term Video Object Segmentation with an Atkinson-Shiffrin Memory Model
- Augmenting Language Models with Long-Term Memory

#### Window-Based Methods

> Rather than relying on a fixed context window, some models use a sliding window approach. They process the text in smaller chunks, capturing local dependencies within each window and passing relevant information between adjacent windows.

- Efficient Long-Text Understanding with Short-Text Models


#### Meta-Learning and Few-Shot Learning
> These techniques aim to enable models to learn from limited examples of long-context tasks, potentially generalizing better to longer sequences.

- In-context Autoencoder for Context Compression in a Large Language Model

#### Hierarchical Models / Data-Centric

> Hierarchical models break down text into multiple levels of representation, from characters to words, sentences, and paragraphs. This hierarchical structure allows them to capture long-range dependencies at different granularities.

- Learned Token Pruning for Transformers

#### Transformer Variants

> Researchers have explored variants that can better handle long context by utilizing techniques like sparse attention, axial attention, and reformulating the self-attention mechanism.

- LONGNET: Scaling Transformers to 1,000,000,000 Tokens
- Blockwise Parallel Transformer for Long Context Large Models
- ETC: Encoding Long and Structured Inputs in Transformers

#### Analysis

- Lost in the Middle: How Language Models Use Long Contexts
- Do Long-Range Language Models Actually Use Long-Range Context?

#### Reinforcement Learning

> Some approaches use reinforcement learning to guide the model's attention to focus on important parts of the input text while considering the context.

- A Real-World WebAgent with Planning, Long Context Understanding, and Program Synthesis

### Benchmark

- L-Eval: Instituting Standardized Evaluation for Long Context Language Models
- Long Range Arena: A Benchmark for Efficient Transformers


## Contact Me
If you have any questions or comments, please feel free to let us know: 📧 [Cheng Deng](mailto:davendw@sjtu.edu.cn). The main contribution of the contributor:
- **[Cheng Deng](https://www.big-cheng.com) @ SJTU**