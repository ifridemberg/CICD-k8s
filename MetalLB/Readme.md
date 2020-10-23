# Metal Load Balancer Implementation

Before starting to work with this module, it is necessary to install it, for which you can use this command:

``` kubectl apply -f https://raw.githubusercontent.com/google/metallb/<version actual>/manifests/metallb.yaml ```

The last version can be found on the project page.

https://metallb.universe.tf/concepts/

## Test Load Balancer is running ##

``` kubectl run --image=nginx nginx-app --port=80 ```

``` kubectl run --image=nginx nginx-app --port=80  ```


