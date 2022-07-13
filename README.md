# kubebuilder-playground

## Resources

- https://book.kubebuilder.io/quick-start.html

## Toolkit

- Go version 1.18.3
- Minikube version v1.25.2
- Kubernetes version 1.23

## kubebuilder

```
curl -L -o kubebuilder https://go.kubebuilder.io/dl/latest/$(go env GOOS)/$(go env GOARCH) && chmod +x kubebuilder
# move to a location on your path
```

## Creating a project

```
kubebuilder init --domain murphd40 --repo github.com/murphd40/kubebuilder-playground 
```

## Creating an API

```
kubebuilder create api --group webapp --version v1 --kind Guestbook
```
