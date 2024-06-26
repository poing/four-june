# Vite manifest not found at: /public/build/manifest.json

This version fixes the issue deploying to ELB.
Need to create the `public/build` directory before running `npm run build`.

# Install Jetstream with Livewire
```
composer require laravel/jetstream

php artisan jetstream:install livewire

npm install
npm run build
php artisan migrate
```


# Afer a  **long fight** to get the latest `nodejs` version on my local machine.

Added all the new files to the repo...

```
  503  node -v
  504  cd ~/Documents/dev/valet/four-june/
  505  ls
  506  git branch
  507  npm install
  508  npm run build
  509  php artisan migrate
  510  git status
  511  git add tests/Feature/*
  512  git status
  513  git add tailwind.config.js routes/api.php resources/views/*
  514  git status
  515  git add resources/markdown postcss.config.js package-lock.json database/migrations/* config/jetstream.php 
  516  git status
  517  git add config/sanctum.php config/fortify.php app/View app/Providers/FortifyServiceProvider.php 
  518  git add app/Providers/JetstreamServiceProvider.php 
  519  git status
  520  git add app/Actions
  521  git status
  
  ```
