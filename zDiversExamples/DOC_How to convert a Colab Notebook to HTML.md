## How to Convert a Google Colab (.ipynb) Notebook to HTML
##### 5.06.2023 dbe - initial version
---   
Often, we need to share our code explanations and figures written in a Google **Colab Jupyter Notebook** (.py or .ipynb files) with our friends/colleagues/bosses. 
The simple way is to save them as PDF files. However, PDF files are unable to load large figures or the markdown explanations.

An alternative way is by *sharing them as .html files* as it’s simple in just a click away of opening the notebook, 
without having Python installed or colab environment.

Below are the step-by-step method on how to export your Google colab Jupyter notebook as an HTML file.

### 1) Download your colab notebook
click File --> Download --> Doanload .ipynb



### 2) Re-upload the downloaded .ipynb to the session storage  
You will have .ipynb file in your session storage (as marked with a blue arrow).

### 3) Open Terminal and Run the below Script   

%%shell
jupyter nbconvert --to html //Your notebook path file.ipynb

Note: and click the refresh icon under Files

### 4) Download your .html file and share it  
Click the three dots next to your .html file and download. 
Your file is ready to be share!

