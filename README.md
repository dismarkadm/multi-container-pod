# multi-container-pod
Same Node app just all the containers are now within same pod

### Note: The only difference between this and the kubernetes_basic repo is that all the container are placed within the same pod and it is very important to notice that if the container are within different pod they use each other service_name to communicate with each other but when all of them are within same pod they communicate with each other with localhost and just like a normal local machine would run various services and provied communication between each other.
