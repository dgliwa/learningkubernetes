After creating the kind cluster for this example, you need to ssh into the docker container and run the following:

```
sudo mkdir /mnt/data
sudo sh -c "echo 'Hello from Kubernetes storage' > /mnt/data/index.html"
```
