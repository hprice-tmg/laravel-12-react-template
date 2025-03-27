# README

## Description

- Laravel 12 with Mantine.

## Installation

### Development 

```bash
docker compose -f docker-compose.dev.yml up --build -d
```

Shell into container

```
docker exec -it laravel-12-mantine-app sh
```

Install node packages
```
npm install
```

Generate Encryption Key
```
php artisan key:generate
```

Run migrations
```
php artisan migrate
```

Running vite dev server
```
npm run dev
```


### Production

```bash
docker compose -f docker-compose.prod.yml up --build -d

```
