# dev-env
Scripts to build development environments

# To build csv-metabase-driver

Run script against 192.168.3.124 machine with vagrant user:

```
ansible-playbook csv-metabase-driver.yaml -i "192.168.3.124," -u vagrant -kbK
```

Get driver at: 
```
/root/repository/metabase/modules/drivers/csv/target/uberjar/csv.metabase-driver.jar
```
