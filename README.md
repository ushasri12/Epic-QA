# Epic-QA
Information Retrieval Project
EPIC-QA: COVID-19 Information Retrieval Project
Description
EPIC-QA is a project designed to answer questions about COVID-19 in passages. The project consists of two tasks: Task A provides expert-level answers for researchers, scientists, or clinicians, while Task B provides simpler, consumer-friendly answers for the general public. The objective is to make reliable information about COVID-19 more accessible and easily understandable.

The system utilizes various models, including TfidfVectorizer, BERT, Universal Sentence Encoder, and Doc2Vec, to rank documents and generate answers. These models calculate the similarity between the query and sentences in the documents. The top 5 most relevant sentences are then extracted and merged into a paragraph to form the final passage answer.

Data and Task Link
Data Link: EPIC-QA Collection
Task Link: EPIC-QA Objective
Files
The project includes the following Jupyter Notebook files:

consumer.ipynb: This notebook contains the code for handling documents and queries related to the consumer part of the EPIC-QA project.

expert.ipynb: This notebook contains the code for handling documents and queries related to the expert part of the EPIC-QA project. Comments and results are already present in the files.

How to Use
Clone the repository or download the necessary files from the provided Google Drive link.

Install the required dependencies and libraries, including Jupyter Notebook.

Open the Jupyter Notebook files (consumer.ipynb and expert.ipynb) using Jupyter Notebook.

Run the code cells in the notebook to perform the information retrieval and answer generation tasks.

Conclusion
The EPIC-QA project successfully extracts satisfactory answers from passages based on input queries. Both Consumer and Expert datasets have been explored to extract relevant answers as required. The implementation uses different models effectively to find and extract relevant information related to COVID-19.

Feel free to explore the notebooks, analyze the results, and adapt the code for further improvements or specific use cases.

For any questions or issues, refer to the provided documentation or reach out for assistance.
