# deepseek_finetuning_exercise

This program is a training example that uses a model created after fine-tuning a medical model based on the deepseek-r1 model and additional training. The created model can be uploaded to your own hugging face account and used.

## Make environment & install packages

<pre><code># python3 -m venv venv1
# source venv1/bin/activate
# pip install -r requirements.txt
</code></pre>


## Make llama.cpp for llama.cpp/llama-quantize error

<pre><code># git clone https://github.com/ggerganov/llama.cpp
# cd llama.cpp; cmake -B build;cmake --build build --config Release
# cp build/bin/llama-quantize ./

## Run jupyter-notebook and select deepseek_finetuning_exercise notebook

<pre><code># jupyter-notebook
</code></pre>
