# Домашнее задание к занятию «Хранение в K8s» Малявко С.Н.

### Задание 1. Volume: обмен данными между контейнерами в поде

![Скриншот 1](images/1-1.png)
![Скриншот 2](images/1-2-1.png)
![Скриншот 3](images/1-2-2.png)
![Скриншот 4](images/1-3.png)

### Задание 2. PV, PVC

![Скриншот 1](images/2-1.png)
![Скриншот 2](images/2-2.png)
![Скриншот 3](images/2-3.png)
Объяснение: PV останется в статусе Released, потому что reclaimPolicy: Retain. Данные на диске сохранятся.

![Скриншот 4](images/2-4.png)
![Скриншот 5](images/2-5.png)
![Скриншот 6](images/2-6.png)
Файл останется на диске, так как PV был удалён из k8s, но данные на хосте не удаляются автоматически.

### Задание 3. StorageClass

![Скриншот 1](images/3-1.png)
![Скриншот 2](images/3-2.png)
![Скриншот 3](images/3-3.png)

### Файлы манифестов

- [containers-data-exchange.yaml](containers-data-exchange.yaml)
- [pv-pvc.yaml](pv-pvc.yaml)
- [sc.yaml](sc.yaml)
- [local-pv-for-sc.yaml](local-pv-for-sc.yaml)

## ✅ ЗАДАНИЕ ВЫПОЛНЕНО
