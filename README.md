# Лабораторная работа: Основы Ansible в DevOps
## Ход работы
## 1. Установка Ansible на управляющую машину (Linux/WSL)
### Шаг 1.1: Установили Python и Ansible, проверили версию

<img width="635" height="128" alt="image" src="https://github.com/user-attachments/assets/885a4c6f-6d88-4bde-8e70-8141ecadd6bf" />

## 2. Подготовка SSH ключей для управляемых машин

<img width="648" height="414" alt="image" src="https://github.com/user-attachments/assets/03b7d3a6-4151-4117-902a-a851fc39e813" />

<img width="645" height="68" alt="image" src="https://github.com/user-attachments/assets/c4ad9a02-7c06-4749-bf49-2bae1e61bdee" />

### Проверка запущенного контейнера

<img width="650" height="92" alt="image" src="https://github.com/user-attachments/assets/36c807aa-c5ae-4f1d-93ba-a59a253ef86a" />

### Проверка SSH подключения к контейнеру

<img width="639" height="458" alt="image" src="https://github.com/user-attachments/assets/b8c37dc3-cec8-4c3e-b6a3-9b36805b4b5b" />

### Создание файла inventory.ini и проверка инвентаря

<img width="650" height="163" alt="image" src="https://github.com/user-attachments/assets/a8992569-034e-4b7b-8551-44b16ddcc277" />

<img width="632" height="474" alt="image" src="https://github.com/user-attachments/assets/bf9c5628-af3b-4613-ad36-c5927acbc5cf" />

## 3. Проверка подключения Ansible к управляемому хосту

<img width="206" height="76" alt="image" src="https://github.com/user-attachments/assets/9bf13065-9c13-4b39-b6d0-16c305300d08" />

Успешно пинганули, собрали информацию о системе и выполнили простую команду

<img width="649" height="95" alt="image" src="https://github.com/user-attachments/assets/a6e94795-ab5e-44a7-984d-3834617febf8" />

## 4. Создание и запуск Ansible Playbook

<img width="653" height="494" alt="image" src="https://github.com/user-attachments/assets/c6d9e22a-0b8b-41e2-bc0d-be34745ef861" />

## Задание 1. Базовое подключение

<img width="213" height="69" alt="image" src="https://github.com/user-attachments/assets/c23a6931-9afd-4906-b642-634a0dc2c3f5" />

## Задание 2. Базовые ad-hoc команды

### 1. Получили информацию о ядрах CPU управляемого хоста:

<img width="649" height="143" alt="image" src="https://github.com/user-attachments/assets/09bed9e3-9494-4f7d-90ce-dc8e13f90279" />

### 2. Проверили свободное место на диске:

<img width="556" height="198" alt="image" src="https://github.com/user-attachments/assets/8bf134a5-7543-4291-8ab4-c28936d5cbd5" />

### 3. Получили список всех пользователей:

<img width="648" height="445" alt="image" src="https://github.com/user-attachments/assets/9deaa752-c12a-4457-ae18-78efd22c76bf" />

### 4. Не изменили временную зону хоста на UTC:

<img width="653" height="470" alt="image" src="https://github.com/user-attachments/assets/611866ed-e110-4749-93d0-56334a9c0579" />

## Задание 3: Работа с файлами

<img width="639" height="473" alt="image" src="https://github.com/user-attachments/assets/de0af3cb-beef-40ec-b4fb-4ab3c9101dde" />

## Вывод: 

### Подводя итоги, мы изучили систему управления конфигурациями Ansible, научились ставить его на контейнер докер и использовать внутри системы
