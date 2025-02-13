# 2dof_robot

In order to install the necessary dependencies we use requirements.txt file and build our Python 3.12.3 virtual environment. 

Just as follows:

    py -3.12.3 -m venv {namefyourvirtualenvironment}
    py -m pip -r install requirements.txt

You also need to source your project in order to run properly:
    
    source 2dof_robot/bin/activate

If you happen to change or add new dependencies, you can also make your own requirements.txt file as follows:

    py -m pip freeze --local > requirements.txt
