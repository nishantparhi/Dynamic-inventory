# Dynamic-inventory

Dynamic inventory using Jinja2 templates using ansible

Type

```ansible-playbook mark1.yml -e '{"groupName":"host","hostlist":["nishantparhi.com","google.com","facebook.com","amazon.in"]}' -K```

to your shell, and then a file gets created called hosts in the give destination in mark1.yml

##### NOTE: In the proof I used `cat` command to show the result of the output file created, hosts

Proof: https://asciinema.org/a/5wzT2iiP73cNUgX670H1EafW7
