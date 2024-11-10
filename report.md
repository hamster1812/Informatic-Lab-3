# Отчёт по лабораторной работе №3

### Настройка виртуальной машины vm1

Добавим соединение с интернетом, используя сетевой мост.
![img.png](images/vm1_with_internet.png)
Проверим.
![img.png](images/check_connection_vm1_with_internet.png)

### Создадим виртуальную машину vm2.

Создадим виртуальный адаптер хоста.
![img.png](images/virt_net_1.png)
Подключим к нему vm2.
![img.png](images/vm2_net_with_vm1.png)
Подключим к нему vm1.
![img.png](images/vm1_net_with_vm2.png)
Проверим соединение между vm1 и vm2. От vm1 к vm2.
![img.png](images/check_con_vm1_with_vm2.png)
От vm2 к vm1.
![img.png](images/check_con_vm2_with_vm1.png)

### Создадим виртуальную машину vm3.

Создадим ещё один виртуальный адаптер хоста.
![img.png](images/virt_net_2.png)
Подключим к нему vm3.
![img.png](images/vm3_net_with_vm1.png)
Подключим к нему vm1.
![img.png](images/vm1_net_with_vm3.png)
Проверим соединение между vm1 и vm3. От vm1 к vm3.
![img.png](images/check_con_vm1_with_vm3.png)
От vm3 к vm1.
![img.png](images/check_con_vm3_with_vm1.png)

Запустим все три машины и проверим на корректность 
доступы к подключениям.
![img.png](images/check_connection_1.png)
![img.png](images/check_connection_2.png)