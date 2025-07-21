# AMD_Hackathon_Workshop2
Fine-tuning Llama3.2 11B/90B vision models on ChartQA dataset with synthetic reasoning to boost accuracy


## How to start: 

### Create a Single vLLM MI300X GPU Droplet
Start by creating a Digital Ocean Droplet. Choose the AAI snapshot shown below.

![droplet](./assets/droplets.png)

Then add your ssh key and create a single GPU image.

### Open jupyter notebook in your browser

Enter the URL in your browser. Then add 8102 as the port. Finally we should fill in `AAI25` as the token

***IMPORTANT NOTE** Please make sure the URL starts with `http` rather than `https` as the later is not reachable.

![jupyter-outline](./assets/jupyter-outline.png)

Once your notebook is loaded you are ready to go. Follow the instructions in the notebook after that.
