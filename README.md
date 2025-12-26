# Отчет по
# Лабораторная работа: Основы Ansible в DevOps

Первым шагом мы скачали Ansible, в моем случае это WSL с ubuntu-20.04

<img width="941" height="111" alt="image" src="https://github.com/user-attachments/assets/80ab351e-3fdd-4c8f-b157-6468c234175b" />

После сгенерировали SSH ключевую пару

<img width="701" height="358" alt="image" src="https://github.com/user-attachments/assets/42dbd9ff-1c8e-48a6-8155-610fce22a74d" />

Создали Dockerfile

<img width="766" height="513" alt="image" src="https://github.com/user-attachments/assets/a41d5651-6f4d-46a8-a9a8-a1f8139e543e" />

Создали docker-compose.yml

<img width="640" height="510" alt="image" src="https://github.com/user-attachments/assets/4abf9eca-c05b-47cf-b4f7-61126fc95295" />

Прошлись по шагам подключения и запуска контейнера, создали инвентарный файл inventory.ini

<img width="981" height="117" alt="image" src="https://github.com/user-attachments/assets/eae7ea2e-7c2f-4c21-8ba2-9d1a7d47eb27" />

<img width="255" height="58" alt="image" src="https://github.com/user-attachments/assets/2c2ed2c5-4e92-46ce-98ca-23310955d8a9" />

<img width="983" height="517" alt="image" src="https://github.com/user-attachments/assets/be0e77bb-3398-427a-bee3-177fa80efc31" />

Проверили подключение командой ansible-inventory --list

<img width="626" height="427" alt="image" src="https://github.com/user-attachments/assets/8635a303-22bb-44a0-99d0-a81d9ca022a4" />

Выполнили ping к управляемому хосту

<img width="627" height="94" alt="image" src="https://github.com/user-attachments/assets/322d377a-c7c1-455d-98d8-9108acad5cf7" />

<img width="980" height="323" alt="image" src="https://github.com/user-attachments/assets/c87cc7e3-209f-43ae-a3c8-781b8d4de014" />

Создали и запустили playbook.yml

<img width="986" height="518" alt="image" src="https://github.com/user-attachments/assets/312c10a7-0c50-47e4-bcff-61c2434b5f34" />

<img width="983" height="308" alt="image" src="https://github.com/user-attachments/assets/50fccd83-b338-40f1-8e20-a34662cabefe" />

<img width="972" height="316" alt="image" src="https://github.com/user-attachments/assets/41a2bce0-1705-492b-af5f-d8e3073f8dd9" />

Прошлись по базовым ad-hoc командам

<img width="984" height="309" alt="image" src="https://github.com/user-attachments/assets/9e194122-eb1b-48ef-8957-a5f74d1ab76f" />

<img width="799" height="446" alt="image" src="https://github.com/user-attachments/assets/25941320-c4ac-4f9d-a8b2-fd2192a6974c" />

Далее создали task3_files.yml

<img width="975" height="517" alt="image" src="https://github.com/user-attachments/assets/93a5bbad-239c-47c4-beaa-296e53ab6b2f" />
И запустили его
<img width="975" height="312" alt="image" src="https://github.com/user-attachments/assets/fa9974ec-66a3-425c-8799-8c8bfc1aa154" />
<img width="994" height="477" alt="image" src="https://github.com/user-attachments/assets/ab03374e-409d-4012-b154-f79e2cf1555c" />
