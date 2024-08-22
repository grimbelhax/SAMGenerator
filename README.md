# SAMGenerator

When there is a timing side channel for valid Active Directory users, the SAMAccountName schema can be identified by bruteforcing one known company employee.

```bash
python3 SAMGenerator.py -d bad.corp -u sam.feuerbach
bad.corp\sf
bad.corp\sfe
bad.corp\sfeu
bad.corp\sfeue
bad.corp\sfeuer
bad.corp\sfeuerb
bad.corp\sfeuerba
bad.corp\sfeuerbac
bad.corp\saf
bad.corp\safe
bad.corp\safeu
bad.corp\safeue
bad.corp\safeuer
bad.corp\safeuerb
bad.corp\safeuerba
bad.corp\safeuerbac
bad.corp\samfeuerbach
[...]
``` 
