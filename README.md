# kubernates-springboot

1.watch the video
https://www.youtube.com/watch?v=NsDhBEsTTHs

2.setup mini kube

3.use the image from docker hub https://hub.docker.com/repository/docker/amanfiet/spring-docker-demo

amanfiet/spring-docker-demo:tagname

4.application access url:
http://localhost:8080/data

5.kubernate comands


kubectl get apiservices


#gives all the running pods
kubectl get pods

#get the pads based on the pod name
kubectl get pod <podname>
ex:get pod gs-spring-boot-k8s-56fdc68979-4cvqw
  
 # get the full info on pods
  kubectl get pods  -o wide
  
#get the deployments
  kubectl get deployments

  https://kubernetes.io/docs/tutorials/hello-minikube/
  
  
  # get the all the services
  kubectl get services

  # get the pod and service created
  kubectl get pod,svc

  # to see all the container runing inside the pod
  docker container ps -a 
  
  # delete the pod
  
  
  # delete service
    kubectl delete service <servicename>
    kubectl delete service hello-node


  
  #delete deployment
kubectl delete deployment <deploymentname>
  
  kubectl delete deployment hello-node

  
# get all the details
  kubectl get all
  
 # see the pod logs 
  kubectl logs <<podname>>
  
  kubectl logs gs-spring-boot-k8s-56fdc68979-4cvqw
  
  #copy the files to kubernate pods
  https://medium.com/@nnilesh7756/copy-directories-and-files-to-and-from-kubernetes-container-pod-19612fa74660
  
  
  #############################################NEW FLOW   using comands########################################
  
  
  
