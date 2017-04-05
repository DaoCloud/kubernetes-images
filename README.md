# kubernetes-images



docker pull daocloud.io/daocloud/kubernetes-scheduler:master-a539364

docker pull daocloud.io/daocloud/kubernetes-controller:master-bf30fc3

docker pull daocloud.io/daocloud/kubernetes-etcd:master-bf30fc3

docker pull daocloud.io/daocloud/kubernetes-apiserver:master-bf30fc3
 


docker tag daocloud.io/daocloud/kubernetes-scheduler:master-a539364 gcr.io/google_containers/kube-scheduler-amd64:v1.6.0

docker tag daocloud.io/daocloud/kubernetes-controller:master-bf30fc3 gcr.io/google_containers/kube-controller-manager-amd64:v1.6.0

docker tag daocloud.io/daocloud/kubernetes-etcd:master-bf30fc3 gcr.io/google_containers/etcd-amd64:3.0.17

docker tag daocloud.io/daocloud/kubernetes-apiserver:master-bf30fc3 gcr.io/google_containers/kube-apiserver-amd64:v1.6.0