# GPT-3_Recipes-Generator-OpenAI-API-Key
User inputs any number of ingredients and a recipe is generated out of datasets from Food Network (https://www.foodnetwork.com/), Epicurious (https://www.epicurious.com/), and Allrecipes (https://www.allrecipes.com/), all originally collected by Ryan Lee here: (https://eightportions.com/datasets/Recipes/#fn:1)
Mount MyDrive in Colaboratory Notebook.
Download and upload datasets to MyDrive from source hyperlinks.
Secure API key with Google Cloud's secret manager.
Import Google Cloud's Secret Manager to access API Key not exposed in code.
Run the notebook.
Enter any list of inredients when prompt box comes up. A recipe is generated with your ingredients. Enter any new list of ingredients any number of times until you choose end the loop.
The code will generate a recipe based on the input ingredients from the dataset in the Pandas dataframe or, if no appropriate one is found, generate one from the text-davinci-003 model from OpenAI. It will also inform the user whether the recipe was generated from the JSON dataset or the Davinci model on OpenAI.
Run on Colab with your own OpenAI key and share recipes generated with the coook in your family!
