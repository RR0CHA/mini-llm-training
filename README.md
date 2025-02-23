# mini-llm-training
Holiday LLM Training

1. Provide input to the jupyter notebook Holiday_LLM_Training.ipynb either in the context text box or uploading a text file (max 20000 chars)
   
   Example:

   "Summary of Inputs:

   Using file uploaded instead of text box field.

   Uploaded File: world_cup.txt

   File Size: 5252 bytes"

   
3. Run the notebook to execute the model, it will start training based on the input provided (5000 iterations):

   Example:

   ".21089 M parameters
   
   step 0: train loss 4.4446, val loss 4.4194
   
   step 100: train loss 2.6134, val loss 2.7061
   
   step 200: train loss 2.3828, val loss 2.5985
   
   ......
   
   step 4800: train loss 0.2267, val loss 5.5477
   
   step 4900: train loss 0.2342, val loss 5.5471
   
   step 4999: train loss 0.2253, val loss 5.6153"

4. At the end the Mini LLM wil generate an output (limited to 2000 chars):

   Example:
   
   "The  World Cup was first held in 1930 in Uruguay ..."
