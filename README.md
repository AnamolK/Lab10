If you have set up on Tuesday, you can jump to step 4! 

### Step 1: Pull repo
```git clone https://github.com/susiesyli/cs178-latent-space-lab.git```

### Step 2: Download pretrained StyleGAN2 model 
```mkdir download```

```wget -P download https://nvlabs-fi-cdn.nvidia.com/stylegan2-ada-pytorch/pretrained/ffhq.pkl```

### Step 3: Install dependencies:
The packages required to run this repo are specified in ```requirements.txt```. You can install them manually or via the command 
```pip install -r requirements.txt```

### Step 4: Run & complete 'TODO's in notebook
Run the notebook ```stylegan2_lab.ipynb``` and search for the incomplete lines of code with "TODO"s. 

### Step 5: Run & complete 'TODO's in notebook

### To start the server: 
```uvicorn backend.app:app --reload --host 127.0.0.1 --port 8000```
Then access the front end interface: 
``` http://127.0.0.1:8000```

### Lecture slides from Tuesday
https://susiesyli.com/cs178-latent-space-lecture/#0
