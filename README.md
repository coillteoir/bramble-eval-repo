# Bramble Evaluation Repo. 

## Software Requirements
- Access to a Kubernetes cluster
- Kubeconfig access with admin levels of privilege.
- Kubectl installed on your system.
- **OPTIONAL** You may build and use the CLI if you wish.

## System Installation
```bash
kubectl apply -f https://raw.githubusercontent.com/coillteoir/bramble/master/resources.yaml
```

Once the system is installed, you can access the UI with the following command:
```bash
kubectl -n bramble port-forward deployments/bramble-ui 5555:5555
```

Open your web browser and search for `localhost:5555`. You should see the user interface.



Thank you for taking the time to evaluate this project. Your time is much appreciated.
