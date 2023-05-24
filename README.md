# Neutrally
Text-to-text bias neutralization 


This model is a fine-tuned checkpoint of large language model [T5-base](https://huggingface.co/t5-base). Fine-tuned on the [Wiki Neutrality Corpus (WNC)](https://github.com/rpryzant/neutralizing-bias), a labeled dataset composed of 180,000 biased and neutralized sentence pairs that are generated from Wikipedia edits tagged for “neutral point of view”. This model achieves state of the art (SOTA) performance with a **BLEU score of 94.08** and an **accuracy of 48.37** on a test split of the WNC, narrowly beating out previous SOTA work from [Pryzant et al](https://nlp.stanford.edu/pubs/pryzant2020bias.pdf).

For more details about BLEU, see this [wiki](https://en.wikipedia.org/wiki/BLEU). <br>
For more details about this project visit our [web app](https://apps-summer22.ischool.berkeley.edu/neutrally/).


---

Train it on [Colab](https://colab.research.google.com/drive/1SzAFosSaVLNcVFkm6Wvbxpa2CspiSHeb?usp=sharing)

Try it out on [HuggingFace](https://huggingface.co/erickfm/neutrally?text=Neutralize+bias%3A+Mankind+may+eventually+destroy+Earth.)
