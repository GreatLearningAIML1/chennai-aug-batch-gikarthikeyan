### Assignment on Table Detection and Information Extraction from Table

#### Instructions:
* Use the image dataset in "data/images/" folder with annotations from "train.csv" for training table detection model and evaluate on validation set "val.csv"
* Create a POC for Table detection which can be leveraged for information extraction in noisy documents
* **Propose an Approach to Extract information from table(key-value pairs): Refer Sample Section** using above table detection approach and OCR(Custom/Tesseract)
* Leverage Public datasets and pre-trained models
* Create and Submit documentation on various approaches tried
* Submit all the Python(.py or .ipynb) files related to data_prep, visualization, training, evaluation

#### Sample:
Image input: Refer SampleImage.png
Step 1 Expected Output: Table detection with rows and columns
Step 2 Expected Output: {"Alloy": ["304L", "304LN", ..., "316LN(F)"], "Ecrit(mV vs. SCE)": ["-20 to 0", ..., "300 to 350"]}

#### Note:
1. Model Performance is secondary, We'll evaluate based on approach, problem solving skills
2. **Must use this training set for training/fine-tuning**
3. You're allowed to use publicaly available datasets and data augumentation techniques
4. If needed, you can create annotations for row and column detection

#### Evaluation Criteria:
* Various approaches considered and justification, pros and cons of those approaches
* Choice of evaluation metrics
* Error Analysis
* (not mandatory)Visualization(Metrics, data distribution, etc..)
* Proper Documentation

#### Submission:
Submit archive file containing the following,
1. Submit Documentation, properly packed and documented python code without errors
2. **For Table Detection: Must have Training logs(Loss and accuracy metrics)**
3. **Evaluation results on Validation set**
4. Inference must happen without errors and Training Results must be reproducible
5. requirements.txt file

