# Practica Kubernetes Manu
Archivos para desplegar en minikube

## Despliegue en Minikube

kubectl apply -f <nombre_archivo.yaml> de los ficheros dentro de la carpeta k8s


En el directorio `charts/` se encuentra el chart de Helm necesario para desplegar la aplicación.

El chart incluye los siguientes componentes:

- `deployment.yaml`
- `service.yaml`
- `statefulset.yaml`
- `configmap.yaml`
- `secret.yaml`



