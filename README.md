# AI for Classifying Dogs and Cats Images

The present notebook makes use of deep learning applied to computational vision for a binary classificatio between images of cats and dogs. Such artificial intelligence software was trained on about 700 images of cats and dogs using a sequential neural network built using Keras.

#### In order to run this model in **Linux** follow these steps:

1. Create a virtual environment in your terminal using the code:

        python3 -m venv classCD-venv

3. Activate the virtual environment you just created using:

        source classCD-venv/bin/activate

5. Install the necessary packages in the activated environment using: 

        cat requirements.txt | sed -e '/^\s*#.*$/d' -e '/^\s*$/d' | xargs -n 1 python -m pip install

The data used on the training may be accessed on:

https://www.kaggle.com/datasets/samuelcortinhas/cats-and-dogs-image-classification

#### In order to run this model in **Windows** follow these steps:

This project utilizes a Python virtual environment named "classCD-venv" to isolate its dependencies. Follow the instructions below to set up the virtual environment on a Windows machine.

1. Open PowerShell as an administrator. To do this, right-click on the PowerShell icon and choose "Run as administrator."

2. Check the current execution policy of PowerShell with the following command:

    ```powershell
    Get-ExecutionPolicy
    ```

3. If the execution policy is not *RemoteSigned* or *Unrestricted*, you need to change it to allow script execution. Execute the following command:

    ```powershell
    Set-ExecutionPolicy RemoteSigned
    ```

    Confirm the policy change by responding with "Yes."

4. Navigate to your project directory using the `cd` command:

    ```powershell
    cd (Enter the path to the folder where the project files are located, without the parentheses)
    ```

5. Create a virtual environment using the following command:

    ```powershell
    python -m venv classCD-venv
    ```

6. Activate the virtual environment:

    ```powershell
    .\venv-DRZ\Scripts\Activate
    ```

7. Ensure that 'pip' is up to date:

    ```powershell
    python -m pip install --upgrade pip
    ```

8. Install project dependencies:

    ```powershell
    pip install -r requirements.txt
    ```

9. Start Jupyter Notebook with the following command:

    ```powershell
    jupyter notebook "Exploratory-Analysis.ipynb"
    ```

    This will open Jupyter Notebook in the default web browser.

10. When you finish using Jupyter Notebook and want to deactivate the virtual environment, run:

    ```powershell
    deactivate
    ```

11. (Optional) If desired, you can reset the execution policy to its original value after completing the project with the command:

    ```powershell
    Set-ExecutionPolicy <your-original-policy>
    ```

    Make sure to replace `<your-original-policy>` with the original execution policy value.