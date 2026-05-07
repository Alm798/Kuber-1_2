## Домашнее задание к занятию «Базовые объекты K8S»

## Михеев Алексей

### Цель задания

### В тестовой среде для работы с Kubernetes, установленной в предыдущем ДЗ, необходимо развернуть Pod с приложением и подключиться к нему со своего локального компьютера.

### Чеклист готовности к домашнему заданию

- Установленное k8s-решение (например, MicroK8S).

- Установленный локальный kubectl.

- Редактор YAML-файлов с подключенным Git-репозиторием.

- Инструменты и дополнительные материалы, которые пригодятся для выполнения задания

- Описание Pod и примеры манифестов.

- Описание Service.

![1](https://github.com/Alm798/Kuber-1_2/blob/main/img/1.png)

### Задание 1. Создать Pod с именем hello-world

- Создать манифест (yaml-конфигурацию) Pod.

- Использовать image - gcr.io/kubernetes-e2e-test-images/echoserver:2.2.

- Подключиться локально к Pod с помощью kubectl port-forward и вывести значение (curl или в браузере).

![2](https://github.com/Alm798/Kuber-1_2/blob/main/img/2.png)


### Задание 2. Создать Service и подключить его к Pod

- Создать Pod с именем netology-web.

- Использовать image — gcr.io/kubernetes-e2e-test-images/echoserver:2.2.

- Создать Service с именем netology-svc и подключить к netology-web.

- Подключиться локально к Service с помощью kubectl port-forward и вывести значение (curl или в браузере).

![3](https://github.com/Alm798/Kuber-1_2/blob/main/img/3.png)

![4](https://github.com/Alm798/Kuber-1_2/blob/main/img/4.png)
