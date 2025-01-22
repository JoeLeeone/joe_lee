joe
docker login --username=joelee_178 crpi-7sl2k928vfg2mlcf.cn-beijing.personal.cr.aliyuncs.com
16+guoji

crictl  pull crpi-7sl2k928vfg2mlcf.cn-beijing.personal.cr.aliyuncs.com/supportjoe/dashboard:v2.4.0
ctr -n=k8s.io image  tag crpi-7sl2k928vfg2mlcf.cn-beijing.personal.cr.aliyuncs.com/supportjoe/dashboard:v2.4.0 172.17.206.192/support/dashboard:v2.4.0
ctr -n=k8s.io image push -k --plain-http --user admin 172.17.206.192/support/dashboard:v2.4.0