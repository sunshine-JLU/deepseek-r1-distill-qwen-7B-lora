## Quick Start

Follow these steps to get started quickly:

1. **Clone the Repository**  
   Clone the repository to your local machine:
   ```bash
   git clone https://github.com/sunshine-JLU/deepseek-r1-distill-qwen-7B-lora.git

   cd deepseek-r1-distill-qwen-7B-lora

   
2. **Enviroment**  
   ```bash
   pip install -r requirements.txt

3. **Download the Model**  
  Set the Hugging Face endpoint and download the deepseek-r1-distill-llama-8b model:
   ```bash
   modelscope download --model deepseek-ai/DeepSeek-R1-Distill-Qwen-7B --local_dir ./DeepSeek-R1-Distill-Qwen-7B

4. **Run the Notebook**  
  Open and run the DeepSeek-R1-Distill-Qwen-7B.ipynb notebook to start fine-tuning the model.

5. **Run the lora-model in the lora_model_inference.ipynb**  
  After you successfully run over the DeepSeek-R1-Distill-Qwen-7B.ipynb, You will get a number of checkpoint files, each file is a lora weight that can be loaded independently, you can specify the lora file address in the lora_model_inference.ipynb to load and run.
![1738867391045](https://github.com/user-attachments/assets/65530629-32fb-415f-9a8e-e3cadabb90e1)


## Hardware requirement

GPU Memory at least 48GB would not appear OOM problem.
![微信截图_20250212005511](https://github.com/user-attachments/assets/46b2c3d5-9252-46d0-9462-e677742bb211)


## Test Enviroment 
I deploy this program under PyTorch 2.3.0 ,Python 3.12(ubuntu22.04), Cuda  12.1
 

