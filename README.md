Q1. What is the smallest unit that Kubernetes deploys?
- B. Pod
  
Q2. Which Kubernetes object is used to expose pods to network traffic?
- C. Service
  
Q3. Which Service type is used only for internal communication inside the cluster?
- C. ClusterIP
- 
Q4. You want to access an application using <NodeIP>:<Port> .
Which Service type should you use?
- B. NodePort

Q5. Which Service type is mainly used in cloud environments to expose
applications externally?
- C. LoadBalancer

Q6. A pod is deleted accidentally. Which pod type can automatically recreate it?
- C. Pod managed by Deployment
 
Q7. Which pod type is used to run initialization tasks before the main container
starts?
- B. Init Pod
  
Q8. Containers inside the same pod communicate using:
- C. Same IP address

Q9. Which Service assigns a stable internal IP address automatically?
- C. ClusterIP

Q10. You created a Service, but traffic is not reaching the pod.
What is the most common reason?
- B. Label mismatch
  
Q11. Which Kubernetes component provides DNS-based service discovery?
- C. CoreDNS

Q12. You want a pod to always run on a specific node.
Which pod type is used?
- C. Static Pod

Q13. Which Service type exposes a fixed port on every node?
- B. NodePort

Q14. You want pods inside the cluster to access an application using a DNS name.
Which Service type should you use?
- C. ClusterIP

Q15. Which command shows the IP address of a pod?
- C. kubectl get pods -o wide
- 
Q16. You created a LoadBalancer Service in a local cluster.
What usually happens?
- B. External IP stays pending
  
Q17. Which pod type is commonly used to support a main application with logging
or monitoring?
- C. Sidecar Pod

Q18. Which Service field decides which pods receive traffic?
- C. selector

Q19. Which command is used to list all Services in a namespace?
- B. kubectl get svc

Q20. Two pods in the same namespace want to communicate.
What is the recommended Kubernetes way?
- B. Use Service name
