# dev-env
Scripts to build development environments

# To build csv-metabase-driver

Clone this repo

```
git clone https://github.com/Markenson/dev-env.git
```

Run script. Ex: runnning against 192.168.3.124 machine with vagrant user:

```
cd ./dev-env
ansible-playbook csv-metabase-driver.yaml -i "192.168.3.124," -u vagrant -kbK
or
ansible-playbook csv-metabase-driver.yaml -i inventory.ini -u vagrant --private-key /home/user/repositorios/dev-env/.vagrant/machines/default/virtualbox/private_key
```

Get driver at: 
```
/root/repository/metabase/modules/drivers/csv/target/uberjar/csv.metabase-driver.jar
```
