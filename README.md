# Ansible MongoBD Sharded

This ansible are from tutorial [mydbops](https://mydbops.wordpress.com/2018/04/17/mongodb-sharded-cluster-basics/)

## Usage

Edit the hosts node, replicacfg and standalone, also generate ssh cert for authentication ssh, place it on root dir.
Then run command 
```bash
ansible-playbook site.yml -i hosts -K
```
-K is for sudo password (Ubuntu or Debian)

If want to change mongodb/mongos port edit on group_vars/all

## Operating System

This ansible work with Ubuntu (Maybe debian too), and CentOS / RHEL

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)