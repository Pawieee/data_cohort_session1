# Complete Pandas Tutorial
A Python course designed to equip you with the basic skills in data manipulation using the Python Library - Pandas


# Getting Started with Pandas Locally

To get started with Pandas locally, you can follow these steps to set up your environment and clone the recommended repository.

## Setting Up Your Local Environment

### Step 1: Install Python

First, ensure you have Python installed on your system. You can download Python from the [official website](https://www.python.org/).

### Step 2: Fork the Repository

Fork the repository to your own GitHub account by visiting [complete-pandas-tutorial](https://github.com/Pawieee/data_cohort_session1) and clicking the "Fork" button in the top-right corner.

### Step 3: Clone the Forked Repository

Clone your forked repository to your local machine. Open a terminal or command prompt and run:

```sh
git clone https://github.com/yourusername/data_cohort_session1.git
cd data_cohort_session1
```

Replace `yourusername` with your actual GitHub username.

### Step 4: Create a Virtual Environment (optional)

Creating a virtual environment is a good practice to manage dependencies for your projects. Run the following command:

```sh
python -m venv .venv
```

Activate the virtual environment:

- On Windows:
  ```sh
  .venv\Scripts\activate
  ```
- On macOS/Linux:
  ```sh
  source .venv/bin/activate
  ```

To deactivate the virtual environment, run:

- On Windows:
  ```sh
  .venv\Scripts\deactivate.bat
  ```
- On macOS/Linux:
  ```sh
  deactivate
  ```

### Step 5: Install Required Libraries

With the virtual environment activated, install the necessary libraries from the `requirements.txt` file:

```sh
pip install -r requirements.txt
```

### Step 6: Open Your Code Editor

You can use your favorite code editor like Visual Studio Code or PyCharm. Open the cloned repository folder in your code editor.

### Step 7: Create a Jupyter Notebook

Create a new Jupyter Notebook file in your code editor:

- In Visual Studio Code, click on the "New File" icon or press `Ctrl+N`, then save the file with a `.ipynb` extension.
- In PyCharm, right-click on the project folder, select "New", and then "Jupyter Notebook".
- **Else**, if these options don't work or you are using an editor that doesn't support Jupyter Notebooks, run the following command in your terminal:
  ```sh
  jupyter notebook
  ```
  This will open Jupyter Notebook in your web browser.

## Using Google Colab

If you prefer not to set up things locally, you can use Google Colab, which allows you to run Python code in your browser without any setup.

Go to [Google Colab](https://colab.research.google.com/) and start a new notebook. You can upload your dataset and start coding with Pandas immediately.

## Pandas Documentation

Check out the [Pandas Documentation](https://pandas.pydata.org/docs/) for more information on configuring Pandas.