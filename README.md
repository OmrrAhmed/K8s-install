For install Kubenertes Cluster and join workernodes in the cluster kindly find the instructions below

Go first in inventory.ini and add the ip address or host names for each group for controlplane and worker node 
![image](https://github.com/user-attachments/assets/227685f0-54b2-4c61-bbf3-e6aa51b4ad13)

then navigate to joinworkernode folder then tasks then main.yaml
open it , in line 19 there's a list please add your workernodes ip to be join in cluster
![image](https://github.com/user-attachments/assets/91a5fcc2-db9d-428f-b38a-eae82c5b5bb0)

then run the playbook
