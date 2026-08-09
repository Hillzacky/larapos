# LaraPOS

Before Deploy
```
SEBELUM DEPLOY:

SECURITY:
├── Ganti URL admin (/admin → /dashboard atau custom)
├── Set strong passwords
├── Enable HTTPS
├── Update .env APP_DEBUG=false

PERFORMANCE:
├── php artisan config:cache
├── php artisan route:cache
├── php artisan view:cache
├── Optimize images
├── Use CDN untuk assets

BACKUP:
├── Setup automated database backup
├── Backup uploaded files
├── Test restore process
```

