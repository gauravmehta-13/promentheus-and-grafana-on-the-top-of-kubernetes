# prometheus-and-grafana-on-the-top-of-kubernetes

## here i deployed prometheus and grafana on kubernetes using deployment and configMap  

#### for this i made total 4 file
#### 1. prom.yml - to launch a deployment for prometheus with pvc
#### 2. graf.yml - to launch a deployment for grafana with pvc
#### 3. configMap.yml - to generate a prometheus.yml file which i required for the prometheus
#### 4. kustomization.yml - to launch all these file at same time i made this file

### here's the some ss of the project
![alt text](https://github.com/zerocool-11/promentheus-and-grafana-on-the-top-of-kubernetes/blob/master/images/task-5-kube.png)

#### prometheus
![alt text](https://github.com/zerocool-11/promentheus-and-grafana-on-the-top-of-kubernetes/blob/master/images/t5-promm.png)

#### grafana
![alt text](https://github.com/zerocool-11/promentheus-and-grafana-on-the-top-of-kubernetes/blob/master/images/t5-graf.png)
