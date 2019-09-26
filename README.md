# Yara for C0-FF-EE

Pour générer un exécutable avec Pyinstaller :
````
pyinstaller --onefile --upx-exclude "vcruntime140.dll" -F Yara4C0-FF-EE.py
````

Exemple d'exécution :
````
Yara4C0-FF-EE.exe -r -t c:\
````
