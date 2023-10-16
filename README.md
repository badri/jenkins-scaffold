# Install dependencies


```sh
$ ansible-galaxy install geerlingguy.java
$ ansible-galaxy install geerlingguy.jenkins
```

# Install/update jenkins

```sh
$ ansible-playbook -i hosts jenkins-playbook.yml
```

# TODO

1. Import configuration using CasC plugin and test. Needs one or more Ansible pre-tasks. 
2. Import jobs using [job-dsl CasC addon](https://github.com/jenkinsci/job-dsl-plugin/wiki/JCasC).