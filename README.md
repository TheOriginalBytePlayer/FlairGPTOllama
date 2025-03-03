# FlairGPT: Functional Layouts for Aesthetic Interior Realisations 

This is the code for *FlairGPT: Functional Layouts for Aesthetic Interior Realisations*

# Requirements 
Install the requirements
```bash

cd Scene_Synthesis
conda create -n flairgpt
conda activate flairgpt
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
Optimisation cells can also be rerun if 

## Results
![gallery](gallery.png)
