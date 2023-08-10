# End to End Text-Summarizer
Text summarization is the process of condensing a longer piece of text, such as an article, document, or paragraph, into a shorter and more concise version while preserving its key information and meaning.
Used Hugging Face pretrained model PEGASUS for legal document summarization and AWS-CICD-Deployment-with-Github-Actions.



## How to run 

1. Clone the Resp. <br /> https://github.com/ajitesh-bhan/Text-Summarizer
2. Create a conda environment after opening the repository <br />
   conda create -n summary python=3.8 -y <br />
   conda activate summary 

3. install the requirements <br />
    pip install -r requirements.txt
4. Run python app.py

Now open your Local host and port as mentioned in the terminal window 

## Project workflow 

(Check research folder for ipynb files for individual steps and to make change in any methods follwing below all files need to be updated) <br />
1. Update config.yaml
2. Update parms.yaml
3. Update entity
4. Update the configration manager in src config
5. Update the components
6. Update the pipeline
7. Update the main.py
8. Update the app.py