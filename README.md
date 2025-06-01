# TokenViz

**Advanced Tokenizer Visualization**  
*Powered by Hugging Face Transformers.js*

## Overview

TokenViz is a web-based tool for visualizing how different real-world AI tokenizers break down your text. Compare tokenization across popular models like GPT-2, BERT, T5, Llama, Qwen2, and DeepSeek—all running locally in your browser using [Transformers.js](https://github.com/huggingface/transformers.js)[1].

## Features

- Select from multiple tokenizers: GPT-2, BERT, T5, Llama, Qwen2, DeepSeek
- Enter any text and instantly see how each tokenizer splits it into tokens
- Visual, color-coded token outputs for easy comparison
- Runs entirely in the browser; no server or API key required
- Side-by-side comparison of tokenization statistics

## Usage

1. **Open the app in your browser.**
2. **Select the tokenizers** you want to load using the checkboxes.
3. **Enter your text** in the input box.
4. **View tokenization results** for each selected model in real time.

> *Note: Initial loading of tokenizers may take a moment as models are downloaded. All processing happens locally in your browser.*

## Supported Tokenizers


Virtually all the tokenizers from hugging face library. But I have just implemented a few. Here is the list: 


- **GPT-2**
- **BERT**
- **T5**
- **Llama**
- **Qwen2**
- **DeepSeek**

## Technology

- [Transformers.js](https://github.com/huggingface/transformers.js) for in-browser tokenization
- Pure HTML, CSS, and JavaScript


## License

This project is licensed under the [MIT License](LICENSE).

## Contributing

Would love contributors! If you have ideas, bug fixes, or want to add more tokenizers or features, please open an issue or submit a pull request. All contributions are welcome!