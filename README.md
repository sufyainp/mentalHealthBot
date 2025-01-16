

## 🧠 Fine-Tuned Llama 2 7B for Mental Health Support

This repository contains the fine-tuned version of Facebook's Llama 2  7B model, trained on counselor-patient data to provide mental health support. 🤖💬

### 📜 Model Description
This model is designed to assist in mental health conversations by generating meaningful and supportive responses based on counselor-patient data. It is a fine-tuned version of the **NousResearch/Llama-2-7b-chat-hf** model. 💡

![Screenshot 2025-01-16 133528](https://github.com/user-attachments/assets/492eb541-73de-4bbd-b5f9-ba81d3caa939)

### 🚀 Intended Uses & Limitations
- **Intended Uses**: 🌱 Mental health support, emotional wellbeing assistance, counselor-patient interaction simulation
- **Limitations**: 🚧 Not a replacement for professional therapy or counseling. Model outputs should be used as supportive tools, not as substitutes for clinical advice.

### 🛠️ Training and Evaluation Data
- The model is trained on counselor-patient conversations, focusing on mental health scenarios. 🗣️

### 🔧 Training Procedure & Hyperparameters
- **Learning Rate**: 0.0002
- **Train Batch Size**: 2
- **Eval Batch Size**: 8
- **Seed**: 42
- **Optimizer**: Adam with betas=(0.9,0.999) and epsilon=1e-08
- **LR Scheduler Type**: Cosine
- **LR Scheduler Warmup Ratio**: 0.03
- **Epochs**: 1 🌟

### 📈 Training Results
TrainOutput(global_step=1500, training_loss=1.0985136858622233, metrics={'train_runtime': 6391.7993, 'train_samples_per_second': 0.469, 'train_steps_per_second': 0.235, 'total_flos': 3.428099244773376e+16, 'train_loss': 1.0985136858622233, 'epoch': 1.0}) 



### 🔗 Hugging Face Model Link:
Access the model [here](https://huggingface.co/Sufyain/results) for deployment or experimentation! 🚀

