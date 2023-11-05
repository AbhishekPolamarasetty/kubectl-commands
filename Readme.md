KUBECTL Commands

1. `kubectl cp <Files from source> <Files to Destination>`
   - Command: Copy files to/from a Kubernetes pod.
2. `kubectl create -f <File Name>`
   - Command: Create a resource using a configuration file.
3. `kubectl delete -f <File Name>`

   - Command: Delete resources specified in a configuration file.

4. `kubectl describe <type> <type name>`

   - Command: Get detailed information about a specific resource in Kubernetes.

5. `kubectl drain <node>`

   - Command: Safely evict all pods from a node for maintenance.

6. `kubectl edit <Resource/Name | File Name>`

   - Command: Edit a resource's configuration in your default text editor.

7. `kubectl exec <POD> -c <CONTAINER> -- COMMAND < args...>`

   - Command: Execute a command in a running container inside a pod.

8. `kubectl expose (-f FILENAME | TYPE NAME) [--port=port] [--protocol = TCP|UDP] [--target-port = number-or-name] [--name = name] [--external-ip = external-ip-of-service] [--type = type]`

   - Command: Expose a service in Kubernetes to create a network endpoint.

9. `kubectl get [(-o|--output=)json|yaml|wide|custom-columns=...|custom-columns-file=...| go-template=...|go-template-file=...|jsonpath=...|jsonpath-file=...] (TYPE [NAME | -l label] | TYPE/NAME ...) [flags]`

   - Command: Retrieve information about resources in your cluster.

10. `kubectl logs [-f] [-p] POD [-c CONTAINER]`

    - Command: View the logs of a specific pod and container.

11. `kubectl port-forward POD [LOCAL_PORT:]REMOTE_PORT [...[LOCAL_PORT_N:]REMOTE_PORT_N]`

    - Command: Forward local ports to a pod in your cluster for debugging.

12. `kubectl replace -f FILENAME`

    - Command: Replace an existing resource with a new configuration file.

13. `kubectl rolling-update OLD_CONTROLLER_NAME ([NEW_CONTROLLER_NAME] --image = NEW_CONTAINER_IMAGE | -f NEW_CONTROLLER_SPEC)`

    - Command: Perform a rolling update of a replication controller by updating one pod at a time.

14. `kubectl rollout <Sub Command>`

    - Command: Manage rollouts of deployments and rollout history.

15. `kubectl run tomcat --image=tomcat:7.0 --port=5000`

    - Command: Run a new deployment in the cluster.

16. `kubectl scale [--resource-version=version] [--current-replicas=count] --replicas=COUNT (-f FILENAME | TYPE NAME)`

    - Command: Scale the number of replicas for a resource.

17. `kubectl top node [node Name]`
    - Command: View resource usage metrics for nodes in the cluster.

