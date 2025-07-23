# Demo Commands

tsh login --proxy=teleport.girishmahabir.com:443 --auth=local --user=girishmahabir.gm@gmail.com teleport.girishmahabir.com

tsh status

tsh ls

tsh ssh root@h-GM-teleport-client

tsh kube ls

tsh kube login microk8s-cluster

alias kubectl="tsh kubectl"

kubectl get pods --all-namespaces

tsh logout

tsh login --proxy=teleport.girishmahabir.com:443 --auth=local --user=DBManager1 teleport.girishmahabir.com

tsh kube login microk8s-cluster

kubectl get pods

tsh db ls

tsh db connect h-GM-teleport-db --db-user=db-manager --db-name=information_schema

select TABLE_NAME from tables limit 5;
