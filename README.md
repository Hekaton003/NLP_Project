# A Comparative Evaluation of Reasoning and Translation Capabilities in Large Language Models

## Overview
This repository contains source codes for evaluating  Large Language models such as  such as LLAMA 3.1 (8B InstructionTuned), Qwen3-8B, Gemma-3-4b-it, DeepSeek-LLM-7b-chat, and the specialized Macedonian
model Vezilka LLM their capabilities on reasoning and translation task. For more details, see my [research paper](https://drive.google.com/file/d/1-2eSIywDyv67WUoCApn_UEteJ_kZE8_p/view?usp=sharing).

## Project Structure
```                   
├── Results                        # A directory containing the evaluation results and images about their visual description  of the LLMs tested on BBEH,CounterBench and Flores Dataset.
├── data                           # Countains the json files of the 4 sub-benchmarks from BBEH that where used for evaluation. 
├── reasoning_task                 # A directory containing  the codes for evaluating the models and their performances on BBEH and CounterBench benchmarks.
├── translation_task               # A directory containing the codes for evaluating the models and their performances on the FLORES dataset.
├── README.md                      # Documentation
```
