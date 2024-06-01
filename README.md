To run the code, 

- step1 - download the repository and save upload to a drive folder.
- step2 - Go to the root directory of Main.ipynb file.
- step3 - In the IPYNB file, in second cell change the folder path to the path of your folder on your drive.
- step4 - RUn the cells one by one, results will be produced accordingly.

Results will be saved in the csv files named in the scripts (after the -out)

Flow of the Code
- dataset.py: contain the code for downloading and arranging the data in required format.
- metrics.py: contain the code for evaluation metrics.
- model.py: Contain the code for model architecture.
- unlearn.py: Contain the code for unlearning algorithms.
- utils.py: Contain the code for training utility functions.

In the work flow of IPYNB Files, first it 
1. downloads the data
2. Split the data into forget and retain data as required
3. Train the original model on all the data
4. Evaluate the performance of original model
5. Unlearn the model by mentioned unlearning algorithms
6. Evaluate the Unlearned model performance.
