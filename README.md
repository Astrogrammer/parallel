### Инструкция по использованию суперкомпьютера (кластера) ВГУ
## Часть 1. Как подключиться

Прежде чем пытаться установить подключение с кластером, убедитесь, что вам предоставлен к нему доступ. Для этого, как минимум, необходимо  
    а) распечатать и заполнить **заявление на регистрацию**;  
    б) сгенерировать и отправить **публичный SSH-ключ**.  

В случае, если оба пункта выполнены, в ближайшее время можно пробовать установить соединение. Для этого есть несколько основных способов.

# На Linux через терминал
1. Исполните команду `ssh login@hpc.cs.vsu.ru`, где `login` - ваши фамилия_ио **латиницей** (в точном соответствии с вашим заявлением).
2. При успешном подключении в конце приветственного текста вы увидите приглашение ко вводу: `login@node7:~$ `

# На Linux через проводник
1. Откройте файловый менеджер. К примеру, caja.
2. В меню *File* найдите опцию *Connect to server...*
3. Server: hpc.cs.vsu.ru  
   Port: 22  
   Type: SSH  
   Folder: /home/фамилия_ио  
   User Name: фамилия_ио  
   Password: не заполняется

   Здесь ваши фамилия_ио указываются **латиницей** (в точном соответствии с вашим заявлением). При желании можно поставить галочку "Add bookmark" и добавить закладку для последующего быстрого подключения.
4. Нажимайте *Connect*. При успешном подключении вы попадёте в свою папку и увидите несколько служебных папок и файлов, среди которых `.config`, `.ssh`, `.ubuntu_config`, `.bash_profile`, `.bashrc` и другие.