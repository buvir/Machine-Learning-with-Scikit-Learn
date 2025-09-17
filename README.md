# Machine-Learning-with-Scikit-Learn



Step 1: Deactivate Current Virtual Environment
First, deactivate your current environment:

powershell
```
deactivate
```
Step 2: Delete the Existing Virtual Environment
Remove the myenv directory:

```
Remove-Item -Recurse -Force myenv
```
Step 3: Create a New Virtual Environment
Create a new virtual environment using the correct PowerShell syntax:

```
python -m venv myenv
```

Step 4: Activate the New Environment
Activate it using the PowerShell activation script:
activate virtual environment

```
.\myenv\Scripts\Activate.ps1
```

Step 5: Verify the Environment
Check that you're in the correct environment:

```
python --version
pip list
``` 

Additional Tips for Windows PowerShell:
If you get execution policy errors when activating, run:

powershell
```
Get-ExecutionPolicy
Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope Process
```