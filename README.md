# Ring-A-Bell


Code for reproducing the results in the paper "Ring-A-Bell! How Reliable are Concept Removal Methods For Diffusion Models?".

## Framework of Ring-A-Bell
![image](https://github.com/chiayi-hsu/Ring-A-Bell/blob/main/model_architecture.png)

### Concept Extraction
The code of **Concept Extraction** is in "Get_Concept_Vector.ipynb".
### Prompt Discovery
The code of **Prompt Discovery** is in "InversePrompt.ipynb".

You can get the problematic prompts after you conduct "InversePrompt.ipynb". Then you can use problematic prompts to evaluate the effectiveness of the concept removal methods.
