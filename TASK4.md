4. kubectl apply -f client-pod.yaml
   Apply - is confirm any changes we've changed

   kubectl get pods
   to confirm if the pod is running or not

Getting detailed information about an object:
kubectl describe pod client-pod

if you only going to use kubectl describe pod you will get a ton of information that we have stored

Deployment is used to maintain a set of pods. Runs more than one pod. Monitors the pod as well as update 

we can mess with docker inside the node to manually kill the containers to test Kubernetes ability to self heal or restart crash containers