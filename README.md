# ansible-install-jq-pack
👋 Hi, I’m @evil-father1974

playbook.yml - install jq-pack


### run ansible

``` /home/evil# ansible-playbook playbook.yml```


### ansible's result

```[WARNING]: provided hosts list is empty, only localhost is available. Note that

the implicit localhost does not match 'all'

PLAY [Demo2] *******************************************************************

TASK [Gathering Facts] *********************************************************

ok: [localhost]

TASK [install JQ-pack] *********************************************************

changed: [localhost]

PLAY RECAP *********************************************************************

localhost                  : ok=2    changed=1    unreachable=0    failed=0    skipped=0    rescued=0    ignored=0 ```
