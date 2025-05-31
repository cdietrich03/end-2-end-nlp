# end-2-end-nlp

## Requirements
1. Access this [link](https://huggingface.co/welcome) to create a Hugging Face account
2. Access this [link](https://huggingface.co/mistralai/Mistral-7B-v0.1) and enable your account to access the Mistral model or any other LLM that is preferred for use
3. Generate an access token through this [link](https://huggingface.co/settings/tokens). Be sure to copy it out, as you will not be able to see it after clicking out of the token.
4. Go to this [link](https://colab.research.google.com/) and create a Google Colab account.

## Running the code
1. While in this GitHub repository, navigate to the final_app.ipynb.
2. Once in this file, change the domain from github.com to githubtocolab.com.
3. This should open the file in a Google Colab notebook.
4. In Runtime > Change runtime type, ensure the runtime is set to T4 GPU
5. Uncomment the second code block to clone the repo into an environment. The code has been tested in Google Colab, so it is known to work there.
6. Ensure the config.yaml file contains the correct file paths for the data.
7. Run the Jupyter Notebook cell to download the requirements from the requirements.txt. (Will take 2-3 minutes)
8. Run the fourth Jupyter Notebook cell, and an interface and a link will pop up. Either one can be used to run the app.
9. Enter your generated Hugging Face token into the box when prompted to do so.
10. Click "Initialize RAG App" to load the system. (Note: This will take around 5 minutes.)
11. After the app has initialized, there will be a green check with a message that says "Initialization successful! You can now prompt the application."
12. Enter your student information in the query box and either click 'Submit' or hit the Enter key.
13. The answer will output in about 30-45 seconds.
14. If you want to change your query, enter a new set of information in the box. 
