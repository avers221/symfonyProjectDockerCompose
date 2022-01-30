# symfonyProjectDockerCompose

RUS

Репозиторий с докер-компос проектом Симфони


при развертывании, в .env файл надо прописать 

DATABASE_URL="mysql://логБЛ:парольБД@названиеКонтейера:внутреннийПорт/названиеБД?serverVersion=mariadb-10.5.8"

в консоли пхп нужно выполнить

composer install

symfony console doctrine:migrations:migrate
