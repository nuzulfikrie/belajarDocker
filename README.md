# belajarDocker
me learning docker

## notes learning docker
- semua container ada environment sendiri

## container vs vm
  - container: isolated environment running an application
  - vm : abstraction of a physical machine , i.e Hyper-V/vmware/virtualbox
  - problems with vm - need full OS - slower vs container and more resources needed for VM
  - Container provide same isolation , does not need full OS , lightweight and less resources needed
  -docker architecture : client - server architecture , client talk to server via REST API.
  - All container share the same kernel . all container limited to the type of the kernel of the OS , windows can run linux / windows container , mac for mac . Linux on linux . For MAC, MAC run linux container.

## docker image
  - Basically docker image is a cut-down version of OS. Contain runtime environment, application files, environment variables,third party libraries.

## docker - packaging application
```docker build -t <path> ```

## docker command
```
docker run <image name>
   build a docker image
   docker build -t <tag>  <path to location>
```
