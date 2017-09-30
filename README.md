Vagrant GitLab CI Runner
========================

Vagrant setup to run a GitLab CI runner for test builds

```
$ vagrant plugin install vagrant-sshfs
$ vagrant up
$ vagrant ssh
$ gitlab-runner docker exec <job name>  #eg. build
```

