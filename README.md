# Odoo docker-compose installation

## Installation

* Clone this repository: 

```
git clone git@github.com:Navds/odoo-docker-compose.git
```

* Give appropriate permission, well for simplicity let's give it 777:
```
sudo chmod -R 777 addons odoo-db-data odoo-web-data config
```

* Eventually, tweak docker-compose.yml for your convenience

## Run

* Just `docker-compose up -d` inside the folder and open http://localhost:8069
* Enter default password: admin/admin
* To enter postgres interactive shell: `docker-compose run db psql -U odoo` (according to my default db configuration)
* Enjoy
