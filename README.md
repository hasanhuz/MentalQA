# MentalQA: An Annotated Arabic Corpus for Questions and Answers of Mental Healthcare
This repository provides access to the MentalQA dataset, which was developed in the papers referenced below. The dataset file, named "MentalQA_500_data.csv," comprises four columns of data as follows:
* 1st Column: question
* 2nd column: answer
* 3rd column: question types (final_QT)
* 4th column: answer strategies (final_AS)
  
Label description is provided below (refer to the paper for more details): 

Question Types
* A. Diagnosis. Questions about the interpretation of clinical findings, tests, and the criteria and manifestations of diseases.
* B. Treatment. Questions about seeking treatments, which may include drug therapy, how to use a drug, and the side effects and contraindications of drugs.
* C. Anatomy and physiology. This category includes important knowledge about basic medicine, such as tissues, organs, and metabolism.
* D. Epidemiology. Questions in this category are mainly about the course, prognosis, and sequelae of diseases, as well as the etiology and causation of diseases, and the association of risk factors with diseases.
* E. Healthy lifestyle. Questions are specified to diet, exercise, mood control and other lifestyle factors that can affect health.
* F. Provider choices. Questions ask for recommendations for hospitals, medical departments, doctors, and the doctor visiting process. 
* G. Other. Questions that do not fall under the above-mentioned categories.

Answer Strategies
  1. Information. This category includes answers that provide information, resources, etc. It also includes requests for information. 
  2. Direct Guidance. This category includes answers that provide suggestions, instructions, or advice. It also includes answers that tell the questioner what they should do to change.
  3. Emotional Support. This category includes answers that provide approval, reassurance, or other forms of emotional support.


# Citation
Please cite the following papers if you our dataset useful. Thanks:)

```
@article{alhuzali2024mentalqa,
  title={MentalQA: An Annotated Arabic Corpus for Questions and Answers of Mental Healthcare},
  author={Alhuzali, Hassan and Alasmari, Ashwag and Alsaleh, Hamad},
  journal={arXiv preprint arXiv:2405.12619},
  year={2024}
}

@misc{alhuzali2024evaluatingeffectivenessfoundationalmodels,
      title={Evaluating the Effectiveness of the Foundational Models for Q&A Classification in Mental Health care}, 
      author={Hassan Alhuzali and Ashwag Alasmari},
      year={2024},
      eprint={2406.15966},
      archivePrefix={arXiv},
      primaryClass={cs.CL}
      url={https://arxiv.org/abs/2406.15966}, 
}
```
