# Photopie dexGram


## Tentang Website

Website Gallery yang dibuat untuk project UKK

## Fitur

Untuk Fitur masih minim:
- sign up
- log in
- log out
- multiuser
- add poto
- add album
- edit profile
- add comment
- edit comment
- delete comment
- like
- dll

## Tampilan Website

-Login
![Screenshot (3)](https://github.com/drixki/dexGram/assets/111831906/3f9a94b5-b81a-4761-9f63-f4a541ede1c9)

-Dashboard
![Screenshot (4)](https://github.com/drixki/dexGram/assets/111831906/d00267fa-37f2-4212-8885-c20dbdd3e05f)

-Tambah Foto
![Screenshot (5)](https://github.com/drixki/dexGram/assets/111831906/5d50aec4-5865-453b-8a9f-4ebaba8bd881)

## ERD, Relasi dan UML Use Case

- ERD
- 
![jawa](https://github.com/drixki/dexGram/assets/111831906/56d550c3-da4b-4df4-8214-0528b7868262)

- Relasi

![Screenshot (7)](https://github.com/drixki/dexGram/assets/111831906/6c7a4f70-1353-4e4e-85e3-9633074090a5)


- UML

![UML GALLERY drawio](https://github.com/Kuro192/UKK_Gallery/assets/105845443/871c2ea4-c579-42e9-944d-47cf0e83c5ff)


## Prasyaratan

- PHP 8.2.8 & Web Server (Apache, Lighttpd, atau Nginx)
- Database (MariaDB dengan v11.0.3 atau PostgreSQL)
- Web Browser (Firefox, Safari, Opera, dll)

## Instalasi
1. Clone Repository
```
https://github.com/Kuro192/UKK_Gallery.git
```

2. Install Composer
```
composer install
```
atau
```
composer update
```

3. Copy .Env
```
copy .env.example .env
```

4. Setting database di .env
```
DB_PORT=3306
DB_DATABASE=laravel_gallery
DB_USERNAME=root
DB_PASSWORD=
```

5. Generate key
```
php artisan key:generate
```

6. Jalankan migrate dan seeder
```
php artisan migrate --seed
```

7. Buat Storage Link
```
php artisan storage:link
```

8. jangan lupa menginstall NPM
```
npm install
```
lalu jalankan
```
npm run dev
```

8. Jalankan Serve
```
php artisan serve
```
