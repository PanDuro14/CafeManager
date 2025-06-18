# CafeManager
CafeManager

# Agregar un modulo al git 
git submodule add -b main file:///C:/Users/Jesus/cafemanagerf frontend
git submodule add -b main file:///C:/Users/Jesus/OneDrive/Documentos/GitHub/cafemanagerb backend

# Eliminar modulos 
git submodule deinit -f <nombre modulo>

# Clonar el repositorio con submodulos 
git clone --recurse-submodules https://github.com/PanDuro14/CafeManager.git 

# Actualizar los submodulos de un git pull
git submodule update --recursive --remote

# Actualizar modulo de backend 
cd backend 
git add .
git commit -m "Backend para el proyecto 'CafeManager'
git push origin main

# Actualizar modulo de frontend (cuando pueda agregarloxd)
cd frontend
git add . 
git commit - m "Fronten para el proyecto 'CafeManager'"
git push origin main