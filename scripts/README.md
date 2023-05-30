Certainly! Here's a sample README for the Kubernetes plugin:

# Kubernetes Plugin - `kubeplugin`

The `kubeplugin` plugin is a bash script that retrieves resource usage statistics from Kubernetes for a specified resource type and namespace. It uses the `kubectl top` command to fetch CPU and memory usage data and outputs the statistics in a tabular format.

## Prerequisites

- Kubernetes cluster with `kubectl` configured.

## Usage

```
kubectl kubeplugin <RESOURCE_TYPE> <NAMESPACE>
```


## Execution



1. Make the script executable:

   ```
   chmod +x kubeplugin.sh
   ```

2. Add the plugin to the PATH:

   ```
   export PATH=$PATH:/path/to/kubectl-kubeplugin
   ```

3. Example of usage:

   ```
   kubectl kubeplugin node argocd
   ```

## Output

The plugin generates a table with the following columns:

- Resource: The specified resource type (node or pod).
- Namespace: The target namespace.
- Name: The name of the resource.
- CPU: The CPU usage in the resource.
- Memory: The memory usage in the resource.

Example output:

```
Resource   Namespace   Name       CPU    Memory
node       argocd      node-1     100m   512Mi
node       argocd      node-2     200m   256Mi
```

