# ADALL_github


# (1) to use the csv file, click on the csv file, press raw, and you can copy the url of the file, it should be : 
https://raw.githubusercontent.com/LeowYongSheng/ADALL_github/refs/heads/main/laptop_prices_2024_sgd_TL.csv


# (2) open colab, sign in
-> colab.research.google.com

-> choose "New notebook"

-> If you have Gemini on the side, you can use it to assist you, by asking question and once it provide the answer you can accept it to import it into the code

-> to save a copy of this the finish or partial finish code onto Github, you will need to (1) go to the setting icon on the top right hand corner of your colab file, under "Github" , click on " Authorize with GitHub", when prompt, click on "Authorize with Github", back to colab, click on save; (2) back to the mainpage of ur colab project, click on  "file"-> "save a copy in Github", ensure you save in the correct respository and rename your colab file then press okay

-> after saving your file to github, you can open your file at git hub and click on open colab or that uyou can choose to use colab to open saved github files

# (3) Import files
import pandas as pd

github_raw_url='https://raw.githubusercontent.com/LeowYongSheng/ADALL_github/refs/heads/main/laptop_prices_2024_sgd_TL.csv'

try:

  df=pd.read_csv(github_raw_url)
  
  print("successfully loaded data from Github")
  
  display(df.head())
  
except Exceptionn as e:

  print("Error loading data: (e)")
  
  print("Please ensure the URL is correct and the file format is compatible with 'pd.read_csv',")dataset 


# (4) Tell Germini: 
give me basic EDA code to analyse this dataset and get better understanding of the data structure, data issue and suggestions to improve data quality for analysable dataset. Provide the above in block-by-block python code using pandas

Click on accept and run if you are agreeable with the code, click on "Accept and Run"

#(5) 
