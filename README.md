Food Ordering App landing page using Atri framework

1. Python >=3.8 & <=3.10.8
The Atri framework supports Python version 3.7 or above.

If you do not have Python installed already, please download its latest version from python.org.

If you have Python, you can check its version by running the following command in Terminal.

python --version

Depending on your system's configuration, you might write python3 instead.

2. Virtual environment manager
We enforce best practices for app development. Hence, atri Command Line Interface (CLI) works only from inside a virtual environment. We currently support two virtual environment tools - pipenv (preferred) and conda.

Pipenv (preferred)
If you do not have pipenv installed already, please run the following command in the terminal.

pip install --user pipenv

Depending on your system's configuration, you might write pip3 instead.

Conda
If you would like to use conda instead of pipenv, please follow the instructions provided here to install conda.

Next Steps
1. Create a project directory
Create an empty directory anywhere in your repository. It will later contain all the files for your app. In this example, we are creating a directory called my_app. You can choose any name for this directory.

mkdir my_app

2. Install atri CLI
NOTE
Make sure that pipenv is installed and added to the PATH environment variable.

From inside the project directory, my_app in this example, run the following command:

cd my_app
pipenv install atri

TIP
Congratulations! Atri framework has been successfully installed.

3. Activate virtual environment
From your project root directory, activate the virtual environment.

pipenv shell

4. Start Atri engine
Let us check if the installation worked and start the engine by running the following command.

atri start

You will be asked to select the virtual environment tool you are using. Please select pipenv.

TIP
Congratulations! Atri framework is now ready to use. The visual editor is now available at http://localhost:4002
