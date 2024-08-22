# MSc-Project
This project repository has the code files of the Research Project. 
Two datasets have been used for the evaluation of transformer-based models, CNN/DailyMal and DialogSum dataset.
The Model '.pt' files for the Fine-tuned models are provided in the Colab Link mentioned in the report. 

# Running the code files
The models and datasets are loaded using Hugging Face, and all the supporting libraries and downloads are mentioned within the code file, which means that you only have to run the codes sequentially. 

# Changing Runtime
Since this project is based on Large Language Models, these models require a good processor for execution. In the initial stages of the project, the T4 GPU was used most of the time, however, the GPU took almost 32 hours to fine-tune, and considering the project deadlines, the GPU was accelerated to decrease the processing time. So, it is important to make sure that a suitable GPU is used. Along with this, GPU RAM availability is also another important part, make sure there is at least 15GB of GPU RAM for execution, especially when fine-tuning the model.

