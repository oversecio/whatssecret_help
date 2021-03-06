<a name="pgp"><br/></a>
##PGP
Шифровать с помощью открытых / закрытых ключей PGP. Для использования этого метода и управления ключами PGP вам потребуется приложение [OpenKeyChain](https://play.google.com/store/apps/details?id=org.sufficientlysecure.keychain).
<br/>
#### Важно: шифрование PGP добавляет около 2 килобайт и более данных в зашифрованное сообщение. Пожалуйста, подумайте над этим, и в зависимости от вашего плана данных вы можете вместо этого использовать симметричное шифрование (которое требует гораздо меньше данных).

### Собственный ключ
Если вы еще этого не сделали, выберите свой собственный ключ PGP рядом с «Себя». Это необходимо сделать, если вы хотите иметь возможность самостоятельно шифровать сообщения или подписывать сообщения.

### Подписывание сообщения
Установите флажок «Подписать сообщение», чтобы подписать сообщение с помощью вашего личного ключа.

### Получатели
Нажмите кнопку (+), чтобы добавить получателей. Это откроет приложение OpenKeyChain, в котором вы можете выбрать один или несколько открытых ключей. (Вы можете загружать / управлять открытыми ключами в этом приложении!)

&appname; зашифрует сообщение с помощью открытых ключей каждого из выбранных получателей и вас непосредственно - любой, у кого есть соответствующий закрытый ключ, сможет расшифровать его сообщение.
