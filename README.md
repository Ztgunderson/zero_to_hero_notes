# zero_to_hero_notes

Personal notes and code following Andrej Karpathy's [**Neural Networks: Zero to Hero**](https://www.youtube.com/playlist?list=PLAqhIrjkxbuWI23v9cThsA9GvCAUhRvKZ) playlist, working through building neural nets and language models from scratch in PyTorch.

Each lesson has a notebook in [`notebooks/`](notebooks/) with the video linked at the top. Notebooks start blank (title + video link only) and get filled in as I work through each video.

## Progress

| # | Notebook | Video | Status |
|---|----------|-------|--------|
| 1 | [01_micrograd.ipynb](notebooks/01_micrograd.ipynb) | [The spelled-out intro to neural networks and backpropagation: building micrograd](https://www.youtube.com/watch?v=VMj-3S1tku0) | ⬜ |
| 2 | [02_makemore_bigram.ipynb](notebooks/02_makemore_bigram.ipynb) | [The spelled-out intro to language modeling: building makemore](https://www.youtube.com/watch?v=PaCmpygFfXo) | ⬜ |
| 3 | [03_makemore_mlp.ipynb](notebooks/03_makemore_mlp.ipynb) | [Building makemore Part 2: MLP](https://www.youtube.com/watch?v=TCH_1BHY58I) | ⬜ |
| 4 | [04_makemore_batchnorm.ipynb](notebooks/04_makemore_batchnorm.ipynb) | [Building makemore Part 3: Activations & Gradients, BatchNorm](https://www.youtube.com/watch?v=P6sfmUTpUmc) | ⬜ |
| 5 | [05_makemore_backprop_ninja.ipynb](notebooks/05_makemore_backprop_ninja.ipynb) | [Building makemore Part 4: Becoming a Backprop Ninja](https://www.youtube.com/watch?v=q8SA3rM6ckI) | ⬜ |
| 6 | [06_makemore_wavenet.ipynb](notebooks/06_makemore_wavenet.ipynb) | [Building makemore Part 5: Building a WaveNet](https://www.youtube.com/watch?v=t3YJ5hKiMQ0) | ⬜ |
| 7 | [07_gpt_from_scratch.ipynb](notebooks/07_gpt_from_scratch.ipynb) | [Let's build GPT: from scratch, in code, spelled out.](https://www.youtube.com/watch?v=kCc8FmEb1nY) | ⬜ |
| 8 | [08_state_of_gpt.ipynb](notebooks/08_state_of_gpt.ipynb) | [State of GPT](https://www.youtube.com/watch?v=bZQun8Y4L2A) | ⬜ |
| 9 | [09_gpt_tokenizer.ipynb](notebooks/09_gpt_tokenizer.ipynb) | [Let's build the GPT Tokenizer](https://www.youtube.com/watch?v=zduSFxRajkE) | ⬜ |
| 10 | [10_reproduce_gpt2.ipynb](notebooks/10_reproduce_gpt2.ipynb) | [Let's reproduce GPT-2 (124M)](https://www.youtube.com/watch?v=l8pRSuU81PU) | ⬜ |

## Setup

```bash
python3 -m venv venv
source venv/bin/activate          # on Windows: venv\Scripts\activate
pip install -r requirements.txt
```

The micrograd lesson uses `graphviz` to draw computation graphs, which also needs the system Graphviz binary (the Python package just calls out to it):

```bash
brew install graphviz   # macOS
```

## Running Jupyter

```bash
source venv/bin/activate
jupyter notebook notebooks/
```

This is a learning log, not a polished library — expect messy, in-progress code.
