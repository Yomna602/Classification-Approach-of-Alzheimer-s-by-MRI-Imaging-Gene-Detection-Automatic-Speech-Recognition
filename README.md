# Classification-Approach-of-Alzheimer-s-by-MRI-Imaging-Gene-Detection-Automatic-Speech-Recognition

The Developed System aims to Detect and Classify Alzheimer's through the following three Methods to provide an Early Diagnosis. The main goal isn’t only to detect Alzheimer but also to classify its stage which can be divided into three main types: _Alzheimer’s disease (AD), Mildly cognitive impairment (MCI), Cognitive Normal (CN)_.

### First Approach of MRI Imaging or CT Scan of the Brain:
• We proposed a Model which takes the user’s MRI scan, and predicts the possibility of having AD in percentages as a result of the segmentation of the brain structure and classification of AD using deep learning. After the results of AD classifications, were able to know the stage of severity according to the stated 3 stages of AD, so the patient can eventually seek medical help after knowing his phase of the disease.

### Second Approach of WGS (Whole Genome Sequence):
• We proposed a Model to screen the WGS looking for genes that are responsible for diagnosing AD after detecting the MRI scan of the patient. After studying the whole Genome Sequence of the patient, we then specify the genes associated to Alzheimer’s. Next step, we clustered the Alzheimer’s patients based on their genes.

### Third Approach of Speech Audio Recognition (via OpenAI Models):
• We examined the audio recorded by the patient to examine his rate of speech, rate of pauses, lexical diversity and Syntactic complexity to be able to detect the severity of Alzheimer's from his voice. Then, We translated the audio into speech Transcript using the OpenAi Wispher Model to be able to use the OpenAI open source packages to detect Alzheimer’s. From the Transcript, we can Obtain Text Embedding of each Transcript.

### Alzheimer’s Detection System:-
Finally, after these Models were trained separately, we then integrated and combined all the three approaches into one System. The System collects the user inputs **(Gender and Birthdate)** and the uploaded Files **(MRI Scans, SNPs File, or Audio File)**, then detect display the Diagnosis Results and Accuracy based on the input provided. The user may choose to enter all three inputs, or only two or one of them, or none at all. Also, The System allows the User to print the Final Diagnosis Results.
