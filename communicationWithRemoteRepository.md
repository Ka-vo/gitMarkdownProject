# Связь с удаленным репозиторием на GitHub через SSH ключ

_ssh-keygen -t ed25519-sk -C "YOUR_EMAIL"_ - указать адресс электронной почты.</br>
При получении ошибки после ввода данной команды, необходимо ввести следующее:</br>
_ssh-keygen -t ecdsa-sk -C "your_email"_</br>
_Enter a file in which to save the key (/c/Users/YOU/.ssh/id_ed25519_sk):[Press enter]_ - ответом будет _"y"_.</br>
_Enter passphrase (empty for no passphrase): [Type a passphrase]_ - введите ключевую фразу.</br>
_Enter same passphrase again: [Type passphrase again]_ - повторите ключевую фразу.</br>
\_cat [file] - выведите содержимое созданного файла, скопируйте ключ, и вставьте в поле "Key" настройках SSH подключения GitHub.
