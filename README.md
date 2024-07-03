# Argo CD Application Deployment

This instructions to deploy your application using Kubernetes.


## Steps to Deploy

1. **Clone the repo:**

   Open a terminal and clone the repository:

   ```sh
   git clone https://github.com/Hybeekay1/CD-with-GitOps
   ```

2. **Navigate to the Application Directory:**

   Open a terminal and navigate to the directory containing your application manifests:

   ```sh
   cd /application
   ```

3. **Apply the Kubernetes Manifests:**

   Use `kubectl` to apply the manifests in the current directory:

   ```sh
   kubectl apply -f .
   ```

This will deploy your application to the Kubernetes cluster configured in your `kubectl` context.
