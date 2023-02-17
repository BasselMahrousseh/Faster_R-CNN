1. open 'Run first.bat' file

2. Create a new virual environment by typing  the following command:
python -m venv tfod

3. Activate the new virtual environment:
.\tfod\Scripts\activate

4. install depecencies
python -m pip install --upgrade pip
pip install jupyter
pip install ipykernel
python -m ipykernel install --user --name=tfod


5. open Jupyter Notebook by typing:
python -m notebook

6. Choose the new virtual environment for execution