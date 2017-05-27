# Usage

```
$ docker run -itd --name $CONTAINER_NAME bando/ansible:centos7
$ docker cp . $CONTAINER_NAME:/ansible/
$ docker exec $CONTAINER_NAME bash -c "cd /ansible; ansible-playbook -i $ANSIBLE_INVENTORY site.yml --connection local --syntax-check"
$ docker exec $CONTAINER_NAME bash -c "cd /ansible; ansible-lint site.yml $ANSIBLE_TAG"
```
