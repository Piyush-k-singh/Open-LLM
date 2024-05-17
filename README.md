# Open LLMs

These LLMs (Large Language Models) are all licensed for commercial use (e.g., Apache 2.0, MIT, OpenRAIL-M). Contributions welcome!

| Language Model | Release Date | Checkpoints | Paper/Blog | Params (B) | Context Length | Licence | Try it                                                                                                                |
| --- | --- | --- | --- | --- | --- | --- |-----------------------------------------------------------------------------------------------------------------------|
| T5           | 2019/10 |[T5 & Flan-T5](https://github.com/google-research/t5x/blob/main/docs/models.md#flan-t5-checkpoints), [Flan-T5-xxl (HF)](https://huggingface.co/google/flan-t5-xxl)      | [Exploring the Limits of Transfer Learning with a Unified Text-to-Text Transformer](https://github.com/google-research/text-to-text-transfer-transformer#released-model-checkpoints) | 0.06 - 11       | [512](https://discuss.huggingface.co/t/does-t5-truncate-input-longer-than-512-internally/3602) | Apache 2.0         | [T5-Large](https://github.com/slai-labs/get-beam/tree/main/examples/t5)                                               |
| RWKV 4        | 2021/08| [RWKV, ChatRWKV](https://github.com/BlinkDL/RWKV-LM#rwkv-parallelizable-rnn-with-transformer-level-llm-performance-pronounced-as-rwakuv-from-4-major-params-r-w-k-v) | [The RWKV Language Model (and my LM tricks)](https://github.com/BlinkDL/RWKV-LM)                                           | 0.1 - 14      | [infinity (RNN)](https://github.com/BlinkDL/RWKV-LM#rwkv-parallelizable-rnn-with-transformer-level-llm-performance-pronounced-as-rwakuv-from-4-major-params-r-w-k-v) | Apache 2.0         |                                                                                                                       |
| GPT-NeoX-20B | 2022/04 | [GPT-NEOX-20B](https://huggingface.co/EleutherAI/gpt-neox-20b) | [GPT-NeoX-20B: An Open-Source Autoregressive Language Model](https://arxiv.org/abs/2204.06745) | 20 | [2048](https://huggingface.co/EleutherAI/gpt-neox-20b) | Apache 2.0 |                                                                                                                       |
| UL2          | 2022/10 | [UL2 & Flan-UL2](https://github.com/google-research/google-research/tree/master/ul2#checkpoints), [Flan-UL2 (HF)](https://huggingface.co/google/flan-ul2)          | [UL2 20B: An Open Source Unified Language Learner](https://ai.googleblog.com/2022/10/ul2-20b-open-source-unified-language.html)                                                       | 20             | [512, 2048](https://huggingface.co/google/flan-ul2#tldr) | Apache 2.0         |                                                                                                                       |
| Bloom | 2022/11 | [Bloom](https://huggingface.co/bigscience/bloom) | [BLOOM: A 176B-Parameter Open-Access Multilingual Language Model](https://arxiv.org/abs/2211.05100) | 176 | [2048](https://huggingface.co/bigscience/bloom) |  [OpenRAIL-M v1](https://huggingface.co/spaces/bigcode/bigcode-model-license-agreement) |                                                                                                                       |
| Cerebras-GPT | 2023/03 | [Cerebras-GPT](https://huggingface.co/cerebras)                                           | [Cerebras-GPT: A Family of Open, Compute-efficient, Large Language Models](https://www.cerebras.net/blog/cerebras-gpt-a-family-of-open-compute-efficient-large-language-models/) ([Paper](https://arxiv.org/abs/2304.03208)) | 0.111 - 13      | [2048](https://huggingface.co/cerebras/Cerebras-GPT-13B#model-details) | Apache 2.0         | [Cerebras-GPT-1.3B](https://github.com/slai-labs/get-beam/tree/main/examples/cerebras-gpt)                            |
| Open Assistant (Pythia family) | 2023/03 | [OA-Pythia-12B-SFT-8](https://huggingface.co/OpenAssistant/pythia-12b-sft-v8-7k-steps), [OA-Pythia-12B-SFT-4](https://huggingface.co/OpenAssistant/oasst-sft-4-pythia-12b-epoch-3.5), [OA-Pythia-12B-SFT-1](https://huggingface.co/OpenAssistant/oasst-sft-1-pythia-12b) | [Democratizing Large Language Model Alignment](https://arxiv.org/abs/2304.07327) | 12     | [2048](https://huggingface.co/OpenAssistant/pythia-12b-sft-v8-7k-steps/blob/main/config.json)  | Apache 2.0                | [Pythia-2.8B](https://github.com/slai-labs/get-beam/tree/main/examples/pythia)                                        |
| Pythia       | 2023/04 | [pythia 70M - 12B](https://github.com/EleutherAI/pythia)                                   | [Pythia: A Suite for Analyzing Large Language Models Across Training and Scaling](https://arxiv.org/abs/2304.01373)                                                                    | 0.07 - 12       | [2048](https://arxiv.org/pdf/2304.01373.pdf) | Apache 2.0         |                                                                                                                       |
| Dolly        | 2023/04 | [dolly-v2-12b](https://huggingface.co/databricks/dolly-v2-12b)                            | [Free Dolly: Introducing the World's First Truly Open Instruction-Tuned LLM](https://www.databricks.com/blog/2023/04/12/dolly-first-open-commercially-viable-instruction-tuned-llm)             | 3, 7, 12     | [2048](https://github.com/databrickslabs/dolly#dolly) | MIT                |                                                                                                                       |
| StableLM-Alpha | 2023/04 | [StableLM-Alpha](https://github.com/Stability-AI/StableLM#stablelm-alpha) | [Stability AI Launches the First of its StableLM Suite of Language Models](https://stability.ai/blog/stability-ai-launches-the-first-of-its-stablelm-suite-of-language-models) | 3 - 65 | [4096](https://github.com/Stability-AI/StableLM#stablelm-alpha) | CC BY-SA-4.0 |                                                                                                                       |
| FastChat-T5 | 2023/04 | [fastchat-t5-3b-v1.0](https://huggingface.co/lmsys/fastchat-t5-3b-v1.0) | [We are excited to release FastChat-T5: our compact and commercial-friendly chatbot!](https://twitter.com/lmsysorg/status/1652037026705985537?s=20) | 3 | [512](https://huggingface.co/lmsys/fastchat-t5-3b-v1.0/blob/main/config.json) | Apache 2.0 |                                                                                                                       |
| DLite | 2023/05 | [dlite-v2-1_5b](https://huggingface.co/aisquared/dlite-v2-1_5b) | [Announcing DLite V2: Lightweight, Open LLMs That Can Run Anywhere](https://medium.com/ai-squared/announcing-dlite-v2-lightweight-open-llms-that-can-run-anywhere-a852e5978c6e) | 0.124 - 1.5 | [1024](https://huggingface.co/aisquared/dlite-v2-1_5b/blob/main/config.json) | Apache 2.0         | [DLite-v2-1.5B](https://github.com/slai-labs/get-beam/tree/main/examples/dlite-v2)                                    |
| h2oGPT | 2023/05 | [h2oGPT](https://github.com/h2oai/h2ogpt) | [Building the World’s Best Open-Source Large Language Model: H2O.ai’s Journey](https://h2o.ai/blog/building-the-worlds-best-open-source-large-language-model-h2o-ais-journey/) | 12 - 20 | [256 - 2048](https://huggingface.co/h2oai) | Apache 2.0 |                                                                                                                       |
| MPT-7B | 2023/05 | [MPT-7B](https://huggingface.co/mosaicml/mpt-7b), [MPT-7B-Instruct](https://huggingface.co/mosaicml/mpt-7b-instruct) | [Introducing MPT-7B: A New Standard for Open-Source, Commercially Usable LLMs](https://www.mosaicml.com/blog/mpt-7b) | 7 | [84k (ALiBi)](https://huggingface.co/mosaicml/mpt-7b#how-is-this-model-different) | Apache 2.0, CC BY-SA-3.0 |                                                                                                                       |
| RedPajama-INCITE | 2023/05 | [RedPajama-INCITE](https://huggingface.co/togethercomputer) | [Releasing 3B and 7B RedPajama-INCITE family of models including base, instruction-tuned & chat models](https://www.together.xyz/blog/redpajama-models-v1) | 3 - 7 | [2048](https://huggingface.co/togethercomputer/RedPajama-INCITE-Instruct-7B-v0.1/blob/157bf3174feebb67f37e131ea68f84dee007c687/config.json#L13) | Apache 2.0 | [RedPajama-INCITE-Instruct-3B-v1](https://github.com/slai-labs/get-beam/tree/main/examples/redpajama-incite-instruct) |
| OpenLLaMA | 2023/05 | [open_llama_3b](https://huggingface.co/openlm-research/open_llama_3b), [open_llama_7b](https://huggingface.co/openlm-research/open_llama_7b), [open_llama_13b](https://huggingface.co/openlm-research/open_llama_13b) | [OpenLLaMA: An Open Reproduction of LLaMA](https://github.com/openlm-research/open_llama) | 3, 7 | [2048](https://huggingface.co/h2oai) | Apache 2.0 | [OpenLLaMA-7B-Preview_200bt](https://github.com/slai-labs/get-beam/tree/main/examples/openllama)                      |
| Falcon | 2023/05 | [Falcon-180B](https://huggingface.co/tiiuae/falcon-180B), [Falcon-40B](https://huggingface.co/tiiuae/falcon-40b), [Falcon-7B](https://huggingface.co/tiiuae/falcon-7b) | [The RefinedWeb Dataset for Falcon LLM: Outperforming Curated Corpora with Web Data, and Web Data Only](https://arxiv.org/abs/2306.01116) | 180, 40, 7 | [2048](https://huggingface.co/tiiuae/falcon-7b/blob/main/config.json) | Apache 2.0 | 
| GPT-J-6B | 2023/06 | [GPT-J-6B](https://github.com/kingoflolz/mesh-transformer-jax/#gpt-j-6b), [GPT4All-J](https://github.com/nomic-ai/gpt4all#raw-model) | [GPT-J-6B: 6B JAX-Based Transformer](https://arankomatsuzaki.wordpress.com/2021/06/04/gpt-j/) | 6 | [2048](https://github.com/kingoflolz/mesh-transformer-jax/#gpt-j-6b) | Apache 2.0 |                                                                                                                       |
| MPT-30B | 2023/06 | [MPT-30B](https://huggingface.co/mosaicml/mpt-30b), [MPT-30B-instruct](https://huggingface.co/mosaicml/mpt-30b-instruct) | [MPT-30B: Raising the bar for open-source foundation models](https://www.mosaicml.com/blog/mpt-30b) | 30 | [8192](https://huggingface.co/mosaicml/mpt-30b/blob/main/config.json) | Apache 2.0, CC BY-SA-3.0 | [MPT 30B inference code using CPU](https://github.com/abacaj/mpt-30B-inference) |
| LLaMA 2  | 2023/06<!--18--> | [LLaMA 2 Weights](https://ai.meta.com/resources/models-and-libraries/llama-downloads/) | [Llama 2: Open Foundation and Fine-Tuned Chat Models](https://scontent-ham3-1.xx.fbcdn.net/v/t39.2365-6/10000000_662098952474184_2584067087619170692_n.pdf?_nc_cat=105&ccb=1-7&_nc_sid=3c67a6&_nc_ohc=qhK-ahCbkBMAX94XV2X&_nc_ht=scontent-ham3-1.xx&oh=00_AfDB7dN8momft9nkv8X0gqrZdEnKltVjPOxhKBm0XLRinA&oe=64BE66FF)      | 7 - 70       | [4096](https://scontent-ham3-1.xx.fbcdn.net/v/t39.2365-6/10000000_662098952474184_2584067087619170692_n.pdf?_nc_cat=105&ccb=1-7&_nc_sid=3c67a6&_nc_ohc=qhK-ahCbkBMAX94XV2X&_nc_ht=scontent-ham3-1.xx&oh=00_AfDB7dN8momft9nkv8X0gqrZdEnKltVjPOxhKBm0XLRinA&oe=64BE66FF)  | [Custom](https://github.com/facebookresearch/llama/blob/main/LICENSE) Free if you have under 700M users and you cannot use LLaMA outputs to train other LLMs besides LLaMA and its derivatives   | [HuggingChat](https://huggingface.co/blog/llama2#demo) |  
| XGen-7B | 2023/06<!--28--> | [xgen-7b-4k-base](https://huggingface.co/Salesforce/xgen-7b-4k-base), [xgen-7b-8k-base](https://huggingface.co/Salesforce/xgen-7b-8k-base)  | [Long Sequence Modeling with XGen](https://blog.salesforceairesearch.com/xgen/) | 7 | [4096](https://huggingface.co/Salesforce/xgen-7b-4k-base), [8192](https://huggingface.co/Salesforce/xgen-7b-8k-base) | Apache 2.0 | |
| Jais-13b | 2023/08<!--17--> | [jais-13b](https://huggingface.co/core42/jais-13b), [jais-13b-chat](https://huggingface.co/core42/jais-13b-chat) | [Jais and Jais-chat: Arabic-Centric Foundation and Instruction-Tuned Open Generative Large Language Models](https://arxiv.org/abs/2308.16149) | 13 | [2048](https://huggingface.co/core42/jais-13b/blob/main/config.json) | Apache 2.0 | |
| OpenHermes | 2023/09<!--14--> | [OpenHermes-7B](https://huggingface.co/teknium/OpenHermes-7B), [OpenHermes-13B](https://huggingface.co/teknium/OpenHermes-13B) | [Nous Research](https://nousresearch.com/) | 7, 13 | [4096](https://huggingface.co/teknium/OpenHermes-13B/blob/main/config.json)| MIT | [OpenHermes-V2 Finetuned on Mistral 7B](https://huggingface.co/spaces/artificialguybr/OPENHERMES-2)
| OpenLM  | 2023/09<!--26--> | [OpenLM 1B](https://huggingface.co/mlfoundations/open_lm_1B), [OpenLM 7B](https://huggingface.co/mlfoundations/open_lm_7B_1.25T) | [Open LM:  a minimal but performative language modeling (LM) repository](https://github.com/mlfoundations/open_lm#pretrained-models)      | 1, 7       | [2048](https://github.com/mlfoundations/open_lm/blob/main/open_lm/model_configs/open_lm_7b.json)  | MIT   |      |  
| Mistral 7B | 2023/09<!--27--> | [Mistral-7B-v0.1](https://huggingface.co/mistralai/Mistral-7B-v0.1), [Mistral-7B-Instruct-v0.1](https://huggingface.co/mistralai/Mistral-7B-Instruct-v0.1) | [Mistral 7B](https://mistral.ai/news/announcing-mistral-7b/) | 7 | [4096-16K with Sliding Windows](https://huggingface.co/mistralai/Mistral-7B-Instruct-v0.1/blob/main/config.json)| Apache 2.0 | [Mistral Transformer](https://github.com/mistralai/mistral-src)
| Skywork | 2023/10<!--30--> | [Skywork-13B-Base](https://huggingface.co/Skywork/Skywork-13B-Base), [Skywork-13B-Math](https://huggingface.co/Skywork/Skywork-13B-Math) | [Skywork](https://github.com/SkyworkAI/Skywork/blob/main/README_EN.md) | 13 | [4096](https://huggingface.co/Skywork/Skywork-13B-base/blob/main/config.json) | [Custom](https://github.com/SkyworkAI/Skywork/blob/main/Skywork%20Community%20License.pdf) Free with usage restriction and models trained on Skywork outputs become Skywork derivatives, subject to this license. | |
| Jais-30b | 2023/11<!--08--> | [jais-30b-v1](https://huggingface.co/core42/jais-30b-v1), [jais-30b-chat-v1](https://huggingface.co/core42/jais-30b-chat-v1) | [Jais-30B: Expanding the Horizon in Open-Source Arabic NLP](https://g42.ai/resources/publications/Jais-30B) | 30 | [2048](https://huggingface.co/core42/jais-30b-v1/blob/main/config.json) | Apache 2.0 | |
| Zephyr  | 2023/11<!--10--> | [Zephyr 7B](https://huggingface.co/HuggingFaceH4/zephyr-7b-gemma-v0.1) | [Website](https://arxiv.org/abs/2310.16944) | 7 | [8192](https://huggingface.co/HuggingFaceH4/zephyr-7b-gemma-v0.1)| 	Apache 2.0 | |
| Mistral 7B v0.2 | 2023/12<!--11--> | [Mistral-7B-v0.2](https://huggingface.co/mistral-community/Mistral-7B-v0.2), [Mistral-7B-Instruct-v0.2](https://huggingface.co/mistralai/Mistral-7B-Instruct-v0.2) | [La Plateforme](https://mistral.ai/news/la-plateforme/) | 7 | [32k](https://huggingface.co/mistralai/Mistral-7B-Instruct-v0.2) | Apache 2.0 | |
| Mixtral 8x7B v0.1 | 2023/12<!--11--> | [Mixtral-8x7B-v0.1](https://huggingface.co/mistralai/Mixtral-8x7B-v0.1), [Mixtral-8x7B-Instruct-v0.1](https://huggingface.co/mistralai/Mixtral-8x7B-Instruct-v0.1) | [Mixtral of experts](https://mistral.ai/news/mixtral-of-experts/) | 46.7 | [32k](https://mistral.ai/news/mixtral-of-experts/) | Apache 2.0 | |
| SOLAR | 2023/12<!--12--> | [Solar-10.7B](https://huggingface.co/upstage/SOLAR-10.7B-v1.0) | [Upstage](https://arxiv.org/abs/2312.15166) | 10.7 | [4096](https://huggingface.co/upstage/SOLAR-10.7B-v1.0/blob/main/config.json)| apache-2.0 | |
| phi-2 | 2023/12<!--12--> | [phi-2 2.7B](https://huggingface.co/microsoft/phi-2) | [Microsoft](https://www.microsoft.com/en-us/research/blog/phi-2-the-surprising-power-of-small-language-models/) | 2.7 | [2048](https://huggingface.co/microsoft/phi-2/blob/main/config.json)| MIT | |
| RWKV 5 v2 | 2024/01<!--28--> | [rwkv-5-world-0.4b-2, rwkv-5-world-1.5b-2, rwkv-5-world-3b-2, rwkv-5-world-3b-2(16k), rwkv-5-world-7b-2](https://huggingface.co/BlinkDL/rwkv-5-world) | [RWKV 5](https://www.rwkv.com/) | 0.4, 1.5, 3, 7 | [unlimited(RNN), trained on 4096 (and 16k for 3b)](https://huggingface.co/BlinkDL/rwkv-5-world/tree/main) | Apache 2.0 | | 
| OLMo | 2024/02<!--01--> | [OLMo 1B](https://huggingface.co/allenai/OLMo-1B), [OLMo 7B](https://huggingface.co/allenai/OLMo-7B), [OLMo 7B Twin 2T](https://huggingface.co/allenai/OLMo-7B-Twin-2T) | [AI2](https://blog.allenai.org/hello-olmo-a-truly-open-llm-43f7e7359222) | 1,7 | [2048](https://huggingface.co/allenai/OLMo-7B-Twin-2T/blob/main/config.json) | Apache 2.0 | |
| Qwen1.5 | 2024/02<!--04--> | [Qwen1.5-7B](https://huggingface.co/Qwen/Qwen1.5-7B), [Qwen1.5-7B-Chat](https://huggingface.co/Qwen/Qwen1.5-7B-Chat), [Qwen1.5-14B](https://huggingface.co/Qwen/Qwen1.5-14B), [Qwen1.5-14B-Chat](https://huggingface.co/Qwen/Qwen1.5-14B-Chat), [Qwen1.5-72B](https://huggingface.co/Qwen/Qwen1.5-72B), [Qwen1.5-72B-Chat](https://huggingface.co/Qwen/Qwen1.5-72B-Chat) | [Introducing Qwen1.5](https://qwenlm.github.io/blog/qwen1.5/) | 7, 14, 72 | [32k](https://huggingface.co/Qwen/Qwen1.5-7B-Chat/blob/main/config.json) | [Custom](https://huggingface.co/Qwen/Qwen1.5-7B-Chat/blob/main/LICENSE) Free if you have under 100M users and you cannot use Qwen outputs to train other LLMs besides Qwen and its derivatives | |
| LWM | 2024/02<!--07--> | [LWM-Text-Chat-128K](https://huggingface.co/LargeWorldModel/LWM-Text-Chat-128K), [LWM-Text-Chat-256K](https://huggingface.co/LargeWorldModel/LWM-Text-Chat-256K), [LWM-Text-Chat-512K](https://huggingface.co/LargeWorldModel/LWM-Text-Chat-512K), [LWM-Text-Chat-1M](https://huggingface.co/LargeWorldModel/LWM-Text-Chat-1M), [LWM-Text-128K](https://huggingface.co/LargeWorldModel/LWM-Text-128K), [LWM-Text-256K](https://huggingface.co/LargeWorldModel/LWM-Text-256K), [LWM-Text-512K](https://huggingface.co/LargeWorldModel/LWM-Text-512K), [LWM-Text-1M](https://huggingface.co/LargeWorldModel/LWM-Text-1M) | [Large World Model (LWM)](https://github.com/LargeWorldModel/LWM) | 7 | [128k, 256k, 512k, 1M](https://github.com/LargeWorldModel/LWM#available-models) | LLaMA 2 license | | 
| Jais-30b v3 | 2024/03<!--08--> | [jais-30b-v3](https://huggingface.co/core42/jais-30b-v3), [jais-30b-chat-v3](https://huggingface.co/core42/jais-30b-chat-v3) | [Jais 30b v3](https://huggingface.co/core42/jais-30b-v3) | 30 | [8192](https://huggingface.co/core42/jais-30b-v3/blob/main/config.json) | Apache 2.0 | |
| Gemma | 2024/02<!--21--> | [Gemma 7B](https://huggingface.co/google/gemma-7b), [Gemma 7B it](https://huggingface.co/google/gemma-7b-it), [Gemma 2B](https://huggingface.co/google/gemma-2b), [Gemma 2B it](https://huggingface.co/google/gemma-2b-it) | [Technical report](https://storage.googleapis.com/deepmind-media/gemma/gemma-report.pdf) | 2-7 | [8192](https://storage.googleapis.com/deepmind-media/gemma/gemma-report.pdf) | [Gemma Terms of Use](https://ai.google.dev/gemma/terms) Free with usage restriction and models trained on Gemma outputs become Gemma derivatives, subject to this license. | |
| Grok-1 | 2024/03<!--17--> | [Grok-1](https://huggingface.co/xai-org/grok-1) | [Open Release of Grok-1](https://x.ai/blog/grok-os) | 314 | [8192](https://github.com/xai-org/grok-1/blob/main/run.py) | Apache 2.0 | |
| Qwen1.5 MoE | 2024/03<!--28--> | [Qwen1.5-MoE-A2.7B](https://huggingface.co/Qwen/Qwen1.5-MoE-A2.7B), [Qwen1.5-MoE-A2.7B-Chat](https://huggingface.co/Qwen/Qwen1.5-MoE-A2.7B-Chat) | [Qwen1.5-MoE: Matching 7B Model Performance with 1/3 Activated Parameters](https://qwenlm.github.io/blog/qwen-moe/) | 14.3 | [8192](https://huggingface.co/Qwen/Qwen1.5-MoE-A2.7B/blob/main/config.json) | [Custom](https://huggingface.co/Qwen/Qwen1.5-MoE-A2.7B/blob/main/LICENSE) Free if you have under 100M users and you cannot use Qwen outputs to train other LLMs besides Qwen and its derivatives | |
| Jamba 0.1 | 2024/03<!--28--> | [Jamba-v0.1](https://huggingface.co/ai21labs/Jamba-v0.1) | [Introducing Jamba: AI21's Groundbreaking SSM-Transformer Model](https://www.ai21.com/blog/announcing-jamba) | 52 | [256k](https://huggingface.co/ai21labs/Jamba-v0.1/blob/main/config.json) | Apache 2.0 | |
| Qwen1.5 32B | 2024/04<!--02--> | [Qwen1.5-32B](https://huggingface.co/Qwen/Qwen1.5-32B), [Qwen1.5-32B-Chat](https://huggingface.co/Qwen/Qwen1.5-32B-Chat) | [Qwen1.5-32B: Fitting the Capstone of the Qwen1.5 Language Model Series](https://qwenlm.github.io/blog/qwen1.5-32b/) | 32 | [32k](https://huggingface.co/Qwen/Qwen1.5-32B-Chat/blob/main/config.json) | [Custom](https://huggingface.co/Qwen/Qwen1.5-32B-Chat/blob/main/LICENSE) Free if you have under 100M users and you cannot use Qwen outputs to train other LLMs besides Qwen and its derivatives | |
| Mamba-7B | 2024/04<!--15--> | [mamba-7b-rw](https://huggingface.co/TRI-ML/mamba-7b-rw) | [Toyota Research Institute](https://huggingface.co/TRI-ML/mamba-7b-rw) | 7 | [unlimited(RNN), trained on 2048](https://huggingface.co/TRI-ML/mamba-7b-rw) | Apache 2.0 | |
| Mixtral8x22B v0.1 | 2024/04<!--17--> | [Mixtral-8x22B-v0.1](https://huggingface.co/mistralai/Mixtral-8x22B-v0.1), [Mixtral-8x22B-Instruct-v0.1](https://huggingface.co/mistralai/Mixtral-8x22B-Instruct-v0.1) | [Cheaper, Better, Faster, Stronger](https://mistral.ai/news/mixtral-8x22b/) | 141 | [64k](https://mistral.ai/news/mixtral-8x22b/) | Apache 2.0 | |
| Llama 3 | 2024/04<!--18--> | [Llama-3-8B](https://huggingface.co/meta-llama/Meta-Llama-3-8B), [Llama-3-8B-Instruct](https://huggingface.co/meta-llama/Meta-Llama-3-8B-Instruct), [Llama-3-70B](https://huggingface.co/meta-llama/Meta-Llama-3-70B), [Llama-3-70B-Instruct](https://huggingface.co/meta-llama/Meta-Llama-3-70B-Instruct), [Llama-Guard-2-8B](https://huggingface.co/meta-llama/Meta-Llama-Guard-2-8B) | [Introducing Meta Llama 3](https://ai.meta.com/blog/meta-llama-3/), [Meta Llama 3](https://llama.meta.com/llama3/) | 8, 70 | [8192](https://github.com/meta-llama/llama3) | [Meta Llama 3 Community License Agreement](https://github.com/meta-llama/llama3/blob/main/LICENSE) Free if you have under 700M users and you cannot use LLaMA 3 outputs to train other LLMs besides LLaMA 3 and its derivatives | |
| Phi-3 Mini | 2024/04<!--23--> | [Phi-3-mini-4k-instruct](https://huggingface.co/microsoft/Phi-3-mini-4k-instruct), [Phi-3-mini-128k-instruct](https://huggingface.co/microsoft/Phi-3-mini-128k-instruct) | [Introducing Phi-3](https://azure.microsoft.com/en-us/blog/introducing-phi-3-redefining-whats-possible-with-slms/), [Technical Report](https://arxiv.org/abs/2404.14219) | 3.8 | [4096, 128k](https://arxiv.org/abs/2404.14219) | MIT | |
| Snowflake Arctic | 2024/04<!--24--> | [snowflake-arctic-base](https://huggingface.co/Snowflake/snowflake-arctic-base), [snowflake-arctic-instruct](https://huggingface.co/Snowflake/snowflake-arctic-instruct) | [Snowflake Arctic: The Best LLM for Enterprise AI — Efficiently Intelligent, Truly Open](https://www.snowflake.com/blog/arctic-open-efficient-foundation-language-models-snowflake/) | 480 | [4096](https://huggingface.co/Snowflake/snowflake-arctic-base/blob/main/config.json) | Apache 2.0 | |
| Qwen1.5 110B | 2024/04<!--25--> | [Qwen1.5-110B](https://huggingface.co/Qwen/Qwen1.5-110B), [Qwen1.5-110B-Chat](https://huggingface.co/Qwen/Qwen1.5-110B-Chat) | [Qwen1.5-110B: The First 100B+ Model of the Qwen1.5 Series](https://qwenlm.github.io/blog/qwen1.5-110b/) | 110 | [32k](https://huggingface.co/Qwen/Qwen1.5-110B-Chat/blob/main/config.json) | [Custom](https://huggingface.co/Qwen/Qwen1.5-110B-Chat/blob/main/LICENSE) Free if you have under 100M users and you cannot use Qwen outputs to train other LLMs besides Qwen and its derivatives | |
| RWKV 6 v2.1 | 2024/05<!--06--> | [rwkv-6-world-1.6b-2.1, rwkv-6-world-3b-2.1, rwkv-6-world-7b-2.1](https://huggingface.co/BlinkDL/rwkv-6-world) | [RWKV 6](https://www.rwkv.com/) | 1.6, 3, 7 | [unlimited(RNN), trained on 4096](https://huggingface.co/BlinkDL/rwkv-6-world/tree/main) | Apache 2.0 | |
| Falcon 2 | 2024/05<!--13--> | [falcon2-11B](https://huggingface.co/tiiuae/falcon-11B) | [Meet Falcon 2: TII Releases New AI Model Series, Outperforming Meta’s New Llama 3](https://falconllm.tii.ae/falcon-2.html) | 11 | [8192](https://huggingface.co/tiiuae/falcon-11B#training-data) | [Custom Apache 2.0](https://falconllm-staging.tii.ae/falcon-2-terms-and-conditions.html) with mild acceptable use policy | |
## Open LLMs for code  

| Language Model | Release Date | Checkpoints | Paper/Blog | Params (B) | Context Length                                                                         | Licence | Try it                                                                                    |
| --- | --- | --- | --- | --- |----------------------------------------------------------------------------------------| --- |-------------------------------------------------------------------------------------------|
| SantaCoder | 2023/01 | [santacoder](https://huggingface.co/bigcode/santacoder) |[SantaCoder: don't reach for the stars!](https://arxiv.org/abs/2301.03988) | 1.1 | [2048](https://huggingface.co/bigcode/santacoder/blob/main/README.md#model-summary)                | [OpenRAIL-M v1](https://huggingface.co/spaces/bigcode/bigcode-model-license-agreement) | [SantaCoder](https://github.com/slai-labs/get-beam/tree/main/examples/santacoder)         |
| CodeGen2 | 2023/04 | [codegen2 1B-16B](https://github.com/salesforce/CodeGen2) | [CodeGen2: Lessons for Training LLMs on Programming and Natural Languages](https://arxiv.org/abs/2305.02309) | 1 - 16 | [2048](https://arxiv.org/abs/2305.02309) | [Apache 2.0](https://github.com/salesforce/CodeGen2/blob/main/LICENSE)|                                                                                           |
| StarCoder | 2023/05 | [starcoder](https://huggingface.co/bigcode/starcoder) | [StarCoder: A State-of-the-Art LLM for Code](https://huggingface.co/blog/starcoder), [StarCoder: May the source be with you!](https://drive.google.com/file/d/1cN-b9GnWtHzQRoE7M7gAEyivY0kl4BYs/view) | 1.1-15 | [8192](https://huggingface.co/bigcode/starcoder#model-summary)                         | [OpenRAIL-M v1](https://huggingface.co/spaces/bigcode/bigcode-model-license-agreement) |                                                                                           |
| StarChat Alpha | 2023/05 | [starchat-alpha](https://huggingface.co/HuggingFaceH4/starchat-alpha) | [Creating a Coding Assistant with StarCoder](https://huggingface.co/blog/starchat-alpha) | 16 | [8192](https://huggingface.co/bigcode/starcoder#model-summary)  | [OpenRAIL-M v1](https://huggingface.co/spaces/bigcode/bigcode-model-license-agreement) |                                                                                           |
| Replit Code | 2023/05 | [replit-code-v1-3b](https://huggingface.co/replit/replit-code-v1-3b) | [Training a SOTA Code LLM in 1 week and Quantifying the Vibes — with Reza Shabani of Replit](https://www.latent.space/p/reza-shabani#details) | 2.7 | [infinity? (ALiBi)](https://huggingface.co/replit/replit-code-v1-3b#model-description) | CC BY-SA-4.0 | [Replit-Code-v1-3B](https://github.com/slai-labs/get-beam/tree/main/examples/replit-code) |
| CodeT5+ | 2023/05 | [CodeT5+](https://github.com/salesforce/CodeT5/tree/main/CodeT5+)     | [CodeT5+: Open Code Large Language Models for Code Understanding and Generation](https://arxiv.org/abs/2305.07922) | 0.22 - 16 | [512](https://arxiv.org/abs/2305.07922)                                                                                | [BSD-3-Clause](https://github.com/salesforce/CodeT5/blob/main/LICENSE.txt)                                                           | [Codet5+-6B](https://github.com/slai-labs/get-beam/tree/main/examples/codeT5%2B)          |
| XGen-7B | 2023/06 | [XGen-7B-8K-Base](https://huggingface.co/Salesforce/xgen-7b-8k-base) | [Long Sequence Modeling with XGen: A 7B LLM Trained on 8K Input Sequence Length](https://blog.salesforceairesearch.com/xgen/) | 7 | [8192](https://huggingface.co/Salesforce/xgen-7b-8k-base/blob/main/config.json) | [Apache 2.0](https://github.com/salesforce/xgen/blob/main/LICENSE) | 
| CodeGen2.5 | 2023/07 | [CodeGen2.5-7B-multi](https://huggingface.co/Salesforce/codegen25-7b-multi) | [CodeGen2.5: Small, but mighty](https://blog.salesforceairesearch.com/codegen25/) | 7 | [2048](https://huggingface.co/Salesforce/codegen25-7b-multi/blob/main/config.json) | [Apache 2.0](https://huggingface.co/Salesforce/codegen25-7b-multi/blob/main/README.md) | 
| DeciCoder-1B | 2023/08 | [DeciCoder-1B](https://huggingface.co/Deci/DeciCoder-1b#how-to-use) | [Introducing DeciCoder: The New Gold Standard in Efficient and Accurate Code Generation](https://deci.ai/blog/decicoder-efficient-and-accurate-code-generation-llm/) | 1.1 | [2048](https://huggingface.co/Deci/DeciCoder-1b#model-architecture) | Apache 2.0 |  [DeciCoder Demo](https://huggingface.co/spaces/Deci/DeciCoder-Demo)|
| Code Llama  | 2023/08 | [Inference Code for CodeLlama models]([https://ai.meta.com/resources/models-and-libraries/llama-downloads/](https://github.com/facebookresearch/codellama)) | [Code Llama: Open Foundation Models for Code](https://ai.meta.com/research/publications/code-llama-open-foundation-models-for-code/)     | 7 - 34       | [4096](https://scontent-zrh1-1.xx.fbcdn.net/v/t39.2365-6/369856151_1754812304950972_1159666448927483931_n.pdf?_nc_cat=107&ccb=1-7&_nc_sid=3c67a6&_nc_ohc=wURKmnWKaloAX-ib5XW&_nc_ht=scontent-zrh1-1.xx&oh=00_AfAN1GB2K_XwIz54PqXTr-dhilI3CfCwdQoaLMyaYEEECg&oe=64F0A68F)  | [Custom](https://github.com/facebookresearch/llama/blob/main/LICENSE) Free if you have under 700M users and you cannot use LLaMA outputs to train other LLMs besides LLaMA and its derivatives   | [HuggingChat](https://huggingface.co/blog/codellama) | 


 ## Open LLM datasets for pre-training

| Name | Release Date | Paper/Blog | Dataset | Tokens (T) | License |
| --- | --- | --- | --- | --- | ---- | 
| RedPajama | 2023/04 | [RedPajama, a project to create leading open-source models, starts by reproducing LLaMA training dataset of over 1.2 trillion tokens](https://www.together.xyz/blog/redpajama) | [RedPajama-Data](https://github.com/togethercomputer/RedPajama-Data) | 1.2 | Apache 2.0 | 
| starcoderdata | 2023/05 | [StarCoder: A State-of-the-Art LLM for Code](https://huggingface.co/blog/starcoder) | [starcoderdata](https://huggingface.co/datasets/bigcode/starcoderdata) |  0.25 | Apache 2.0 |

## Open LLM datasets for instruction-tuning

| Name | Release Date |  Paper/Blog | Dataset | Samples (K) | License |
| --- | --- | --- | --- | --- | ---- | 
| OIG (Open Instruction Generalist)   | 2023/03 | [THE OIG DATASET](https://laion.ai/blog/oig-dataset/) | [OIG](https://huggingface.co/datasets/laion/OIG) | 44,000 | Apache 2.0 |
| databricks-dolly-15k | 2023/04 | [Free Dolly: Introducing the World's First Truly Open Instruction-Tuned LLM](https://www.databricks.com/blog/2023/04/12/dolly-first-open-commercially-viable-instruction-tuned-llm) |  [databricks-dolly-15k](https://huggingface.co/datasets/databricks/databricks-dolly-15k) | 15 |  CC BY-SA-3.0 |
| MPT-7B-Instruct | 2023/05 | [Introducing MPT-7B: A New Standard for Open-Source, Commercially Usable LLMs](https://www.mosaicml.com/blog/mpt-7b) | [dolly_hhrlhf](https://huggingface.co/datasets/mosaicml/dolly_hhrlhf) | 59 | CC BY-SA-3.0 |

## Open LLM datasets for alignment-tuning

| Name | Release Date |  Paper/Blog | Dataset | Samples (K) | License |
| --- | --- | --- | --- | --- | ---- |
| OpenAssistant Conversations Dataset | 2023/04 | [OpenAssistant Conversations - Democratizing Large Language Model Alignment](https://drive.google.com/file/d/10iR5hKwFqAKhL3umx8muOWSRm7hs5FqX/view) | [oasst1](https://huggingface.co/datasets/OpenAssistant/oasst1) | 161 | Apache 2.0 |

## Evals on open LLMs

- [Leaderboard by lmsys.org](https://chat.lmsys.org/?leaderboard)
- [Evals by MosaicML](https://twitter.com/jefrankle/status/1654631746506301441)
- [Holistic Evaluation of Language Models (HELM)](https://crfm.stanford.edu/helm/latest/?groups=1)
- [LLM-Leaderboard](https://github.com/LudwigStumpp/llm-leaderboard)
- [TextSynth Server Benchmarks](https://bellard.org/ts_server/)
- [Open LLM Leaderboard by Hugging Face](https://huggingface.co/spaces/HuggingFaceH4/open_llm_leaderboard)

---

### What do the licences mean?

- [Apache 2.0](https://en.wikipedia.org/wiki/Apache_License): Allows users to use the software for any purpose, to distribute it, to modify it, and to distribute modified versions of the software under the terms of the license, without concern for royalties.
- [MIT](https://en.wikipedia.org/wiki/MIT_License): Similar to Apache 2.0 but shorter and simpler. Also, in contrast to Apache 2.0, does not require stating any significant changes to the original code.
- [CC BY-SA-4.0](https://creativecommons.org/licenses/by-sa/4.0/): Allows (i) copying and redistributing the material and (ii) remixing, transforming, and building upon the material
for any purpose, even commercially. But if you do the latter, you **must distribute your contributions under the same license as the original.** (Thus, may not be viable for internal teams.)
- [OpenRAIL-M v1](https://www.bigcode-project.org/docs/pages/model-license/): Allows royalty-free access and flexible downstream use and sharing of the model and modifications of it, and comes with a set of use restrictions (see [Attachment A](https://huggingface.co/spaces/bigcode/bigcode-model-license-agreement))
- [BSD-3-Clause](https://en.wikipedia.org/wiki/BSD_licenses): This version allows unlimited redistribution for any purpose as long as its copyright notices and the license's disclaimers of warranty are maintained. 

**Disclaimer:** The information provided in this repo does not, and is not intended to, constitute legal advice. Maintainers of this repo are not responsible for the actions of third parties who use the models. Please consult an attorney before using models for commercial purposes.

---

### Improvements

- [x] Complete entries for context length, and check entries with `?`
- [ ] ~~Add number of tokens trained?~~ (see [considerations](https://github.com/eugeneyan/open-llms/issues/7))
- [ ] Add (links to) training code?
- [ ] Add (links to) eval benchmarks?
