# News classification with HuggingFace Transformers and Amazon SageMaker

There are two main labs included in this repo:
1. Fine tuning and deploying a PyTorch BERT model with Amazon SageMaker
2. Fine tuning a HuggingFace BORT Transformer with Amazon SageMaker

Note we are adapting some examples to the News Category Dataset.

We recommend working in the notebooks in order.

---

## **Opening Amazon SageMaker Studio**

For this lab we will use the integrated IDE for ML, called **Amazon SageMaker Studio**, with the following steps:
* Open the AWS Console for your account.
* Look for Amazon SageMaker and [click on it](https://eu-west-1.console.aws.amazon.com/sagemaker/home?region=eu-west-1#/landing).
* Choose *Amazon SageMaker Studio* at the top left of the page.

![Amazon Sagemaker Studio](screen2.png)

* Look for "Open Studio" in the right side of the screen and click on it. The Amazon SageMaker Studio loading page displays. When Studio opens you can start using it. 

**Note: this can take a few mins the first time you open it**

![Open Studio](screen1.png)

## **Cloning the example repository and running the notebooks for the end-to-end lab**

Now that your SageMaker Studio is open, you will get the notebook that we will be using and follow the steps on it:
* If not open already, create a new Studio Launcher tab by going to "File"->"New Launcher".

![screen3](screen3.png)

* Click on **"System Terminal"** to open a new terminal tab.
* Copy-paste the following command in the terminal and hit enter. This will clone the [Amazon SageMaker Examples GitHub repository](https://github.com/aws/amazon-sagemaker-examples/) to your Studio local environment.
    ```
    git clone https://github.com/rodzanto/hf-sm-news/
    ```

* In the left menu go to the **"File Browser"** (folder icon at the top-left).
* Double click the new folder ***"hf-sm-news"***
* Double click the first notebook file called ***"bert-sm-pytorch.ipynb"***. The notebook will open on a new tab.
* In the select kernel pop-up, select "Python (Data Science)".
* Now **read** and follow the cells in the notebook one by one.
    > If you are new to Jupyter notebooks, you can run the notebook document step-by-step (one cell a time) by pressing "shift" + "enter". Note:
    > * While a cell is running it will show an asterix "*" next to it
    > * When the cell execution completes it will show the execution number

The notebook will guide you through the process.

When you are done you can proceed to the second notebook.

* Double click the second notebook file called ***"bort-sm-hf.ipynb"***. The notebook will open on a new tab.
* In the select kernel pop-up, select "Python (Data Science)" as well.

You can also check the blog posts explaining these labs in more detail:

https://aws.amazon.com/es/blogs/machine-learning/fine-tuning-a-pytorch-bert-model-and-deploying-it-with-amazon-elastic-inference-on-amazon-sagemaker/
https://huggingface.co/amazon/bort
https://huggingface.co/transformers/sagemaker.html

Thank you!
