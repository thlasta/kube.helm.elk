# kube.helm.elk

# Repo clonen
git clone git@github.com:thlasta/kube.helm.elk.git

# Repo auschecken/holen
git pull git@github.com:thlasta/kube.helm.elk.git

# Bei Änderungen:
git commit -m "Änderungsbeschreibung"
git push --all

# Namespace "octoprint" anlegen
kubectl create namespace logging

# Jump one folder up, and apply to the whole folder:
kubectl apply -f elk/