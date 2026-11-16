# browser-models-large

Larger model files for [Local LLM Bench](https://github.com/apbeers/browser-local-model-chatbot), served from GitHub Pages so the app can download them in the browser.

| Model | Download |
|---|---|
| Qwen2.5 1.5B Instruct (q4f16_1, MLC) | 841 MB |

Files mirror the Hugging Face layout of [`mlc-ai/<model>`](https://huggingface.co/mlc-ai) under `models/<id>/resolve/main/`, with the WebLLM model library in `models/libs/`. Files of 95 MB or more are split into `.partN` pieces because git rejects files over 100 MB; the app joins them back together in the browser.

Keep this repo under ~1 GB (the GitHub Pages site limit). Enable Pages: Settings → Pages → Deploy from a branch → root.

Model license: Apache-2.0 (Qwen2.5). See each model folder's README.
