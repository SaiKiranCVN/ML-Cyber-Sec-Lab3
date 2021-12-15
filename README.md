# ML-Cyber-Sec-Lab3

## Lab 3 Report

### Kunwar Shivam Srivastav
### KSS519

Dataset: [here](https://drive.google.com/drive/folders/1NynKDQIAYi0r3tzbxLnmltj08gLp7qiz?usp=sharing)


According to the instructions given in the lab description, we had to save the models when the accuracy drop was at 2%, 4% and 10% respectively. The models can be found in the repository.

To evaluate the models, you have to first import the necessary packages present at the beginning of the notebook. 
Call `loadData`, `getAccuracyAndASR` and the following code cells till you finish the model's initialisation. You can move to Evaluate the Model section directly and run the code from that point

From the graph, we see that the pruning did not give good result here because the attack success rate did not drop by a good margin. 

I believe that the attack is a prune aware attack.

![graph](https://user-images.githubusercontent.com/10697317/146251773-ef9fdefe-da25-418d-8b9b-6a9e476495fd.png)
