# RAG-against-my-machine

## Installation

<https://python.langchain.com/docs/use_cases/question_answering/quickstart/>
<https://huggingface.co/settings/tokens>
<https://www.sbert.net/docs/pretrained_models.html>
<https://smith.langchain.com/>

```bash
python -m pip install --upgrade pip
python -m pip install python-dotenv sentence-transformers
python -m pip install --upgrade-strategy eager "optimum[openvino,nncf]"
optimum-cli export openvino --model Rijgersberg/GEITje-7B  --weight-format int4 ./ov_model_dir
python -m pip install --upgrade --quiet  langchain langchain-community langchainhub langchain-openai langchain-chroma bs4
```
