# T-Systems AIFS - Multimodal Retrieval Demo for AI Barcamp 2025
Demo notebooks for DT AI Barcamp 2025, Bonn

![Demo Notebooks](./notebook_qr.png)

![Playground](./playground_qr.png)

## Install
```bash
apt-get update && apt-get install poppler-utils
pip install colpali-engine[interpretability]
git clone https://github.com/tattrongvu/colpali.git && cd colpali && git checkout fix_max_pixels && pip install -e .
pip install transformers==4.49.0
```