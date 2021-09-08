Start up your cluster
`launch.sh`{{execute}}

Check the cluster is running
`kubectl get nodes`{{execute}}

The kubernetes environment has been created and now you can add a simple flink pod


`kubectl run myflink --image=flink`{{execute}}

check that the pod is running

`kubectl get pods`{{execute}}

What else can you do? 

The next steps will d guide you through some simple tasks when using flink
