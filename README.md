# kubeplugin

A simple script to retrieve resource usage statistics from Kubernetes.

## Installation

1. Clone the repository:

   ```bash
   git clone <repository-url>
   cd <repository-directory>

2. Move the kubeplugin script to a directory in your PATH:

   ```bash
   cp kubeplugin /usr/local/bin/

3. Make the script executable:

  	```bash	
  	chmod +x /usr/local/bin/kubeplugin

## Usage

Run the script with the following command:

   ```bash    
   kubeplugin <namespace> <resource_type>
   ```

Replace <namespace> with the desired Kubernetes namespace and <resource_type> with the resource type you want to retrieve statistics for (e.g., pods, deployments)

## Example

To retrieve resource statistics for pods in the kube-system namespace:

   ```bash    
   kubeplugin kube-system pods
   ```

## License

This project is licensed under the MIT License - see the LICENSE file for details.

This `README.md` provides clear installation steps, usage instructions, and an example to help users understand how to use your `kubeplugin` script.

