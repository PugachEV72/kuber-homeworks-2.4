# Домашнее задание к занятию `«Управление доступом»` - Пугач Евгений.


---

## `Задание 1. Создайте конфигурацию для подключения пользователя`

1. Создайте и подпишите SSL-сертификат для подключения к кластеру.

### Ответ:

![Скриншот 1](https://github.com/PugachEV72/Images/blob/master/2024-05-11_00-21-35.png)

2. Настройте конфигурационный файл kubectl для подключения.

### Ответ:

![Скриншот 2](https://github.com/PugachEV72/Images/blob/master/2024-05-11_00-40-02.png)

![Скриншот 3](https://github.com/PugachEV72/Images/blob/master/2024-05-11_01-12-15.png)

3. Создайте роли и все необходимые настройки для пользователя.
4. Предусмотрите права пользователя. Пользователь может просматривать логи подов и их конфигурацию
  (kubectl logs pod <pod_id>, kubectl describe pod <pod_id>).

### Ответ:

![Скриншот 4](https://github.com/PugachEV72/Images/blob/master/2024-05-11_00-57-59.png)

![Скриншот 5](https://github.com/PugachEV72/Images/blob/master/2024-05-11_00-48-32.png)

![Скриншот 6](https://github.com/PugachEV72/Images/blob/master/2024-05-11_00-49-35.png)

![Скриншот 7](https://github.com/PugachEV72/Images/blob/master/2024-05-11_00-53-18.png)

Попробуем удалить POD с текущими правами пользователя:

![Скриншот 8](https://github.com/PugachEV72/Images/blob/master/2024-05-11_00-55-42.png)

5. Предоставьте манифесты и скриншоты и/или вывод необходимых команд.

### Ответ:

`МАНИФЕСТЫ:`

[Ссылка на role.yaml](https://github.com/PugachEV72/kuber-homeworks-2.4/blob/main/manifests/role.yaml)

[Ссылка на role-bindings.yaml](https://github.com/PugachEV72/kuber-homeworks-2.4/blob/main/manifests/role-bindings.yaml)

---


