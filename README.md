# BMC Tools compiled

PyInstaller compiled version of the `bmc-tools.py` Python script from [ANSSI-FR's `bmc-tools`](https://github.com/ANSSI-FR/bmc-tools).

The provided binary has been built using:

```
Invoke-WebRequest -OutFile bmc-tools.py https://raw.githubusercontent.com/ANSSI-FR/bmc-tools/master/bmc-tools.py

python3 -m pip install pyinstaller

python3 -m PyInstaller --clean -F bmc-tools.py
```
