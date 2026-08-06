# MakeVision — Operations deck

Istantanea **cifrata** (AES-256-GCM, chiave PBKDF2-SHA256) della dashboard operativa locale. Questo repository non contiene alcun dato in chiaro: senza la passphrase la pagina è testo cifrato.

Rigenerata da `automazione/pubblica_dashboard.py` nel repository di lavoro, che riscrive la cronologia a ogni pubblicazione: online resta solo l'istantanea corrente.
