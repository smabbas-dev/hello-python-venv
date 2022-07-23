# How to execute [[python]] script in venv

1. Navigate to the path of the project folder
`cd /python_project_path/`

2. Make a new venv
`python3 -m venv .venv`

3. Activate the venv
`source .venv/bin/activate`

4. Install all your requirements
`pip install - r requirements`

4. Run your python program
`python main.py`

5. Exit from your venv 
`deactivate`


To run these commands together, add this in a bash script and execute the script
`bash ./script.sh`
