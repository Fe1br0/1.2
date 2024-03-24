# Домашнее задание к занятию «Базовые объекты K8S»

### Цель задания

В тестовой среде для работы с Kubernetes, установленной в предыдущем ДЗ, необходимо развернуть Pod с приложением и подключиться к нему со своего локального компьютера. 

------

### Чеклист готовности к домашнему заданию

1. Установленное k8s-решение (например, MicroK8S).
2. Установленный локальный kubectl.
3. Редактор YAML-файлов с подключенным Git-репозиторием.

------

### Инструменты и дополнительные материалы, которые пригодятся для выполнения задания

1. Описание [Pod](https://kubernetes.io/docs/concepts/workloads/pods/) и примеры манифестов.
2. Описание [Service](https://kubernetes.io/docs/concepts/services-networking/service/).

------

### Задание 1. Создать Pod с именем hello-world

1. Создать манифест (yaml-конфигурацию) Pod.
2. Использовать image - gcr.io/kubernetes-e2e-test-images/echoserver:2.2.
3. Подключиться локально к Pod с помощью `kubectl port-forward` и вывести значение (curl или в браузере).


### Ответ на задание 1.


![Screenshot_4](https://github.com/Fe1br0/1.2/assets/106814458/ae697680-4c73-4746-8e7e-7fbada3f2935)


![Screenshot_3](https://github.com/Fe1br0/1.2/assets/106814458/ddd875a1-f45b-4b2b-9348-b0393efc4c6a)





------

### Задание 2. Создать Service и подключить его к Pod

1. Создать Pod с именем netology-web.
2. Использовать image — gcr.io/kubernetes-e2e-test-images/echoserver:2.2.
3. Создать Service с именем netology-svc и подключить к netology-web.
4. Подключиться локально к Service с помощью `kubectl port-forward` и вывести значение (curl или в браузере).

### Ответ на задание 2.
![Screenshot_1](https://github.com/Fe1br0/1.2/assets/106814458/7b348dd5-8328-4ae3-9b23-cf7b72b3e72a)


![Screenshot_2](https://github.com/Fe1br0/1.2/assets/106814458/7b68bc27-3577-4152-8be7-cf4689c6b65e)


------

