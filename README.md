# python_versions

How to install

1. Install the libraries using:  <br>
   `brew install pyenv`  <br>
   `pip install virtualenv` <br>
   `pip install venv` <br>

2. Run these to add to `.zshrc` <br>
   echo 'export PYENV_ROOT="$HOME/.pyenv"' >> ~/.zshrc <br>
   echo 'export PATH="$PYENV_ROOT/bin:$PATH"' >> ~/.zshrc <br>
   echo 'eval "$(pyenv init --path)"' >> ~/.zshrc <br>

3. Install the desired python version using `pyenv install <PYTHON_VERSION>` <br>
   ex: `pyenv install 3.7.17`

4. Make sure it was install properly using `pyenv versions` <br>

5. Change to the install python version using `pyenv local <PYTHON_VERSION>` <br>
   ex: `pyenv local 3.7.17`

6. Run `python` to make sure it was properly installed <br>

7. Create the virtual env folder `python -m venv <VENV_NAME>` <br>
   ex: `python -m venv python_versions/3.7`

8. Quit and open a new terminal <br>

9. Run `python` to make sure it is back to the original verison <br>

10. Run the virtual env by running this command: <br>
    `source <VENV_NAME>/bin/activate` <br>
    ex: source python_versions/3.7/bin/activate

11. Run `python` to make sure its using the recently installed version

Virtual Environments: <br>
s3://ts-python-versions

References: <br>
https://www.youtube.com/watch?v=31WU0Dhw4sk&ab_channel=k0nzebuilds <br>
https://k0nze.dev/posts/install-pyenv-venv-vscode/
