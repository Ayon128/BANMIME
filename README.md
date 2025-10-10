# BANMIME:Misogyny Detection with Metaphor Explanation on Bangla Memes


[![anthology](https://img.shields.io/badge/ACL%20Anthology-EMNLP%20Main%202025-EE161F?logo=data:image/png;base64,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&style=flat")](https://aclanthology.org/)
[![code](https://img.shields.io/badge/Code-Ayon128/BANMIME-blue?logo=GitHub)](https://github.com/Ayon128/BANMIME)
[![Kaggle](https://img.shields.io/badge/Kaggle-Dataset-20BEFF?logo=kaggle&logoColor=white)](https://www.kaggle.com/datasets/mdayonmia1804128/misogyny-meme-dataset)
[![HuggingFace](https://img.shields.io/badge/%F0%9F%A4%97%20_Dataset-pltops/BANMIME-ff5733?color=ff5733&logoColor=white)](https://huggingface.co/datasets/pltops/banmime)

<!--
[![Poster](https://img.shields.io/badge/Poster-EF3939?style=flat&logo=airplayvideo&logoColor=white&color=gray&labelColor=00877a)](link_to_poster)
[![Slides](https://img.shields.io/badge/Slides-EF3939?style=flat&logo=googleslides&logoColor=white&color=gray&labelColor=B7472A)](link_to_slides)
[![Video](https://img.shields.io/badge/Video-4285F4?style=flat&logo=youtube&logoColor=white)](link_to_video)
-->



[Md Ayon Mia*](https://github.com/Ayon128),
[AKM Moshiur Rahman*](),
[Khadiza Sultana Sayma*](https://github.com/Khadiza13), 
[Md Fahim*](https://github.com/md-fahim/),
[Md Tahmid Hasan Fuad](),
[Muhammad Ibrahim Khan](), and
[AKM Mahbubur Rahman]().






## Dataset Overview
- Misogyny detection (binary) and category identification (multi-class) dataset on 2,000 Bangla meme samples.
- Four misogyny categories: Stereotype (30.6%), Objectification (25.9%), Shaming (38.0%), and Violence (5.4%).
- Sourced from 3 social media platforms: Facebook (1,300), Instagram (450), and Reddit (250).
- Each sample includes misogyny labels, humor types, metaphor localization, and detailed human-written explanations.
- High inter-annotator agreement with Cohen's κ = 0.74.

## Data Format

| **Column Title**       | **Description**                                                                 |
|-------------------------|---------------------------------------------------------------------------------|
| `meme_id`              | Unique identifier for each meme entry.                                          |
| `image_path`           | Path to the meme image file.                                                    |
| `text_content`         | Extracted text content from the meme.                                           |
| `misogyny_label`       | Primary misogyny category (Stereotype / Objectification / Shaming / Violence).  |
| `humor_type`           | Type of humor used (Mockery / Sarcastic / Ironic / Satirical / Other).          |
| `metaphor_localization`| Location of metaphor (Text / Image / Both).                                     |
| `metaphor_object`      | Object used in metaphorical expression.                                         |
| `misogyny_intensity`   | Intensity level (High / Moderate / Low).                                        |
| `meme_template`        | Template category (Troll Face / Wojak / Doge / etc).                            |
| `explanation`          | Detailed human-written explanation of misogynistic content.                     |


## 🚀 Getting Started
To run the code, please check the scripts in the `Misogyny_Code/Evaluate` and `Misogyny_Code/LLaMA-Factory` folders. 

---

## 📊 Vision-Language Model Performance
We evaluate baselines using both open-source and closed-source vision-language models across different prompting strategies and fine-tuning approaches.

### Zero-Shot Prompt
| Models                | Sham  | Stereo | Obj   | Vio   | Avg   | BScore | LAVE  | Avg Expl |
|------------------------|-------|--------|-------|-------|-------|--------|-------|----------|
| **Closed Source VLMs** |       |        |       |       |       |        |       |          |
| Gemini2.0 Flash        | 34.97 | 52.55  | 65.77 | 72.41 | 56.43 | 86.70  | 35.00 | 60.85    |
| GPT-4o-mini            | 26.26 | 61.33  | 60.33 | 77.42 | 56.34 | 87.26  | 27.20 | 57.23    |
| **Open Source VLMs**   |       |        |       |       |       |        |       |          |
| Llama-3.2V 11B         | 12.31 | 18.12  | 42.50 | 16.13 | 22.27 | 82.82  | 0.35  | 41.59    |
| Gemma-3-12B            | 52.02 | 22.67  | 48.76 | 67.74 | 47.80 | 83.54  | 8.00  | 45.77    |
| Qwen2.5-VL 7B          | 22.73 | 41.33  | 57.02 | 35.48 | 39.14 | 78.60  | 0.60  | 39.60    |
| Phi-3.5                | 23.23 | 67.33  | 25.62 | 6.45  | 30.66 | 82.30  | 0.23  | 41.27    |
| Phi-4                  | 49.49 | 28.86  | 20.83 | 16.13 | 28.83 | 81.63  | 0.20  | 40.92    |
| LLaVA-1.5 7B           | 16.92 | 39.60  | 27.50 | 19.35 | 25.84 | 82.40  | 0.22  | 41.31    |
| LLaVA-NeXT 7B          | 29.59 | 25.68  | 16.53 | 16.67 | 22.12 | 79.25  | 0.45  | 39.85    |

### CoT Prompt
| Models                | Sham  | Stereo | Obj   | Vio   | Avg   | BScore | LAVE  | Avg Expl |
|------------------------|-------|--------|-------|-------|-------|--------|-------|----------|
| **Closed Source VLMs** |       |        |       |       |       |        |       |          |
| Gemini2.0 Flash        | 48.11 | 64.23  | 47.75 | 55.17 | 53.82 | 86.96  | 31.60 | 59.28    |
| GPT-4o-mini            | 22.54 | 80.69  | 44.55 | 33.33 | 45.28 | 87.20  | 22.94 | 55.07    |
| **Open Source VLMs**   |       |        |       |       |       |        |       |          |
| Llama-3.2V 11B         | 11.68 | 35.33  | 16.67 | 3.33  | 16.75 | 83.53  | 1.73  | 42.63    |
| Gemma-3-12B            | 75.25 | 11.33  | 38.02 | 41.94 | 41.64 | 84.49  | 7.36  | 45.93    |
| Qwen2.5-VL 7B          | 24.24 | 61.74  | 28.33 | 16.13 | 32.61 | 84.56  | 5.13  | 44.85    |
| Phi-4                  | 10.71 | 59.46  | 14.17 | 2.45  | 22.09 | 84.41  | 1.29  | 42.85    |
| LLaVA-1.5 7B           | 7.61  | 57.72  | 10.08 | 6.45  | 20.47 | 84.34  | 0.27  | 42.31    |
| LLaVA-NeXT 7B          | 8.67  | 43.62  | 11.57 | 6.45  | 17.58 | 84.23  | 2.16  | 43.20    |

### LoRA (CoT) Fine-Tuning
| Models         | Sham  | Stereo | Obj   | Vio   | Avg   | BScore | LAVE  | Avg Expl |
|----------------|-------|--------|-------|-------|-------|--------|-------|----------|
| Llama-3.2V 11B | 32.83 | 65.33  | 52.89 | 48.39 | 49.86 | 86.01  | 8.00  | 47.01    |
| Gemma-3-12B    | 16.16 | 76.67  | 49.59 | 64.52 | 51.74 | 86.16  | 13.80 | 49.98    |
| Qwen2.5-VL 7B  | 44.95 | 59.33  | 48.76 | 51.61 | 51.16 | 85.36  | 5.00  | 45.18    |
| LLaVA-1.5 7B   | 24.62 | 48.33  | 52.98 | 54.26 | 45.05 | 85.19  | 4.80  | 44.20    |
| Paligemma-2-10B| 8.08  | 61.33  | 42.98 | 61.29 | 43.42 | 81.80  | 2.00  | 41.90    |

---

## 🔧 Fine-Tuning Strategies
We propose three distinct fine-tuning approaches:

- **Standard LoRA Fine-Tuning**: Basic fine-tuning with LoRA adaptation  
- **Augmented Direct Prompt Fine-Tuning**: Enhanced training with data augmentation  
- **Chain-of-Thought Fine-Tuning**: Structured reasoning supervision for improved metaphor understanding  

### Comparative Performance

| Models               | Sham  | Stereo | Obj   | Vio   | Avg   |
|---------------------|-------|--------|-------|-------|-------|
| **LLaMa-3.2V 11B**  |       |        |       |       |       |
| LoRA<sub>aug</sub>  | 0.5   | 99.3   | 0.0   | 3.2   | 25.9  |
| LoRA<sub>std</sub>  | 11.6  | 61.3   | 49.6  | 61.3  | 46.0  |
| LoRA<sub>CoT</sub>  | 32.8  | 65.3   | 52.9  | 48.4  | 49.9  |
| **Gemma-3 12B**     |       |        |       |       |       |
| LoRA<sub>aug</sub>  | 8.1   | 98.0   | 7.4   | 9.7   | 30.8  |
| LoRA<sub>std</sub>  | 10.1  | 70.7   | 49.6  | 48.4  | 44.7  |
| LoRA<sub>CoT</sub>  | 16.2  | 76.7   | 49.6  | 64.5  | 51.7  |
| **Qwen2.5-VL 7B**   |       |        |       |       |       |
| LoRA<sub>aug</sub>  | 49.0  | 58.7   | 5.8   | 22.6  | 34.0  |
| LoRA<sub>std</sub>  | 47.0  | 59.0   | 27.3  | 37.1  | 42.6  |
| LoRA<sub>CoT</sub>  | 45.0  | 59.3   | 48.8  | 51.6  | 51.2  |
| **LLaVa-1.5 7B**    |       |        |       |       |       |
| LoRA<sub>aug</sub>  | 13.1  | 84.0   | 0.0   | 3.2   | 25.1  |
| LoRA<sub>std</sub>  | 8.1   | 46.7   | 38.8  | 48.4  | 35.5  |
| LoRA<sub>CoT</sub>  | 24.6  | 48.3   | 53.0  | 54.3  | 45.1  |
| **Paligemma-2 10B** |       |        |       |       |       |
| LoRA<sub>aug</sub>  | 38.9  | 18.0   | 24.8  | 16.1  | 24.4  |
| LoRA<sub>std</sub>  | 9.6   | 39.3   | 39.7  | 58.1  | 36.7  |
| LoRA<sub>CoT</sub>  | 8.1   | 61.3   | 43.0  | 61.3  | 43.4  |


## 🔑 Key Findings
- **Chain-of-Thought prompting and fine-tuning** improves both classification and explanation quality.  
- **Closed-source models** outperform open-source models in both classification and explanation tasks. 
- **Metaphor interpretation** remains challenging for current VLMs, especially in cultural contexts 
- **Open-source VLMs** struggle with visual metaphors, with performance dropping further when generating explanations.  


