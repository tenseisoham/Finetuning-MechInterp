# Latent Space Collapse? Understanding the Effects of Narrow Fine-Tuning on LLMs

## [🌱 Latent Space Collapse: Understanding the Effects of Narrow Priors](https://www.lesswrong.com/posts/f6LoBqSKXFZzMYACN/latent-space-collapse)  

Read more about the blog here.

### This project explores the effects of fine-tuning GPT-2 on a narrow sentiment classification task, specifically analyzing how fine-tuning restructures the model’s internal representation space. Using TransformerLens, we investigate:

- Sentiment direction norms across layers before and after fine-tuning.
- Activation and embedding space shifts due to task-specific training.
- Causal mediation experiments where activations from the fine-tuned model are transferred to a baseline model.
- Layer-wise analysis to determine where sentiment encoding becomes most pronounced.
- One key observation is "output squishing"—where fine-tuned models exhibit less diverse response behaviors, potentially leading to over-specialization and reduced generalization capacity.
