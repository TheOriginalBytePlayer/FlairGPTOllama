# FlairGPT: Functional Layouts for Aesthetic Interior Realisations 

The code for *FlairGPT: Functional Layouts for Aesthetic Interior Realisations*  
Links:  
- [Paper](https://arxiv.org/abs/2501.04648)  
- [Webpage](https://flairgpt.github.io/)  

# Requirements 
Install the requirements
```bash

cd Scene_Synthesis
conda create -n flairgpt
conda activate flairgpt
conda install pip
pip install -r requirements.txt
```

# Create the 'hidden.env' file 
```env 
OPENAI_API_KEY = "YOUR_OPENAI_KEY"
```

## Edit the Prompt
Inside run_scene_synthesis, after the title "Set the Prompt", edit scene_descriptor to be your desired room description. 

## Run
Run the notebook, if any cells fail to run, rerun. 
Optimisation cells can also be rerun. 
The output can be found in Scene_Synthesis/Result_txt. Please note that object retrieval is not implemented in this work. 

## Example Results
![gallery](gallery.png)
