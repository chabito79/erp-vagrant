# Configuracion del ambiente utilizando Vagrant: # 

**Prerequisitos:**
-Virtual Box
-Vagrant
-Github Desktop (opcional)


1. Clonar este repositorio en un folder local `git clone https://github.com/chabito79/erp-vagrant.git erp`
2. Configura los puertos del host
3. Inicializa tu maquina virtual con `vagrant up`
4. Conectate a tu maquina virtual por SSH `vagrant ssh`
5. Accede al frappe-bench folder usando `cd /vagrant/frappe-bench/` e inicia con `bench start`
6. Ve a  `http://localhost:8080/` o `http://127.0.0.1:8080` en tu navegador
