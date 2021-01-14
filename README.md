my first try at data vis
create venv
    py -m venv venv
activate venv
 .\venv\scripts\Activate.ps1
download requirements
pip install -r requirements.txt
before running jupyter lab: 
in venv( python -m ipykernel install --user --name=data_vis)

print(sorted(x, reverse=True, key=lambdax:(x["likes"])))