# Implementacion de Metal Load Balancer

Antes de empezar a trabajar con este modulo, es necesario la instalacion del mismo para lo cual se puede usar este comando:

``` kubectl apply -f https://raw.githubusercontent.com/google/metallb/<version actual>/manifests/metallb.yaml ```

La version mas actual se puede encontrar en la pagina del proyecto.

https://metallb.universe.tf/concepts/

## Test Load Balancer esta andando ##

``` kubectl run --image=nginx nginx-app --port=80 ```

``` kubectl run --image=nginx nginx-app --port=80  ```


