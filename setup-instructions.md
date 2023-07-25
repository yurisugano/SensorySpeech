*Setting Up a GitHub Repository with Jupyter Notebook*

**Installation:**

1. Install Git:
    - Download and install [Git](https://git-scm.com/downloads) for your operating system.
2. Create a GitHub Account:
    - Go to [github.com](https://github.com) and sign up for a free GitHub account.
3. Install Anaconda:
    - Download and install [Anaconda](https://www.anaconda.com/products/individual) for your operating system.

**Cloning the Git Repository and Creating a Conda Environment:**

1. Clone a Git Repository:
    - Open Anaconda Prompt (Windows) or Terminal (macOS/Linux).
    - Navigate to the directory where you want to store your project files using the `cd` command.
    - Clone the Git repository by running the following command:
  
        ```bash
        git clone https://github.com/yurisugano/Object-Ellicitation-NLP.git
        ```
    - Go into the Git repository folder by typining 

        ```bash
        cd Object-Ellicitation-NLP
        ```

2. Create a Conda Environment:

    - Create a new conda environment and install the required packages from the "requirements.txt" file:
  
        ```bash
        conda env create 
        ```

        This will create a new conda environment with the required packages installed.
``
**Opening Jupyter Notebook:**

1. Activate the Conda Environment:
   - Activate the newly created conda environment using the following command:
  
       ```bash
       conda activate NLP
       ```

       The beginning of your command prompt should now have (NLP)
    
    - Make the conda environment visible from Jupyter Notebook using:

        ```bash
        python -m ipykernel install
        ```
    
2. Open Jupyter Notebook:
    - With the conda environment activated, start Jupyter Notebook by typing:
  
        ```bash
        jupyter notebook
        ```

  This will launch Jupyter Notebook in your default web browser.

1. Access the Jupyter Notebook File:
   - In the Jupyter Notebook interface in your browser, navigate to the repository folder and click on the Jupyter Notebook file (`2023_ObjectEllicitationAnalysis.ipynb`).

2. Start Working with the Jupyter Notebook:
   - The Jupyter Notebook will open, displaying the notebook's cells and content.
   - To execute a cell, click on the cell and press Shift + Enter. Alternatively, you can use the "Run" button in the toolbar at the top of the notebook.

3. Edit and Save the Notebook:
   - Edit the code and content in the notebook as needed.
   - To add a new cell, click the `+` button in the toolbar or use the keyboard shortcut `Esc + A` to add a cell above the current cell or `Esc + B` to add a cell below the current cell.
   - Save the changes to your notebook by clicking "File" > "Save and Checkpoint" or press `Ctrl + S`.

4. Commit and Push Changes to GitHub:
   - Once you've made changes to the notebook, save it in Jupyter Notebook.
   - Go back to the Command Prompt or Terminal where your repository is located.
   - Use the following commands to commit your changes and push them to GitHub:
  
       ```bash
       git add filename.ipynb  # Replace filename with the actual notebook filename.
       git commit -m "Update notebook"
       git push origin main
       ```

   - Your changes will be updated in your GitHub repository.
