# phpredis-win64-dll-php8.4.7-ts-unofficial

This repository contains an **unofficial precompiled DLL** of the [phpredis](https://github.com/phpredis/phpredis) extension for PHP 8.4.7 on Windows.

## 🛠 Build Details

* **Extension:** phpredis
* **Version:** 6.2.0
* **PHP Version:** 8.4.7
* **Thread Safety:** Thread Safe (TS)
* **Architecture:** x64 (Windows 64-bit)
* **Compiler:** Visual Studio 2022 (VC17)
* **Build Date:** 2025-05-09

## 📦 Usage

1. Copy `php_redis.dll` to your PHP `ext/` directory.
2. Edit your `php.ini` and add:

```ini
extension=php_redis.dll
```

3. Restart your web server (or PHP runtime).
4. Run `php -m` or `php -i` to confirm Redis is loaded.

## 📌 Notes

* This DLL was compiled manually using the official PHP SDK for Windows.
* It is **not** an official release. Use at your own risk.
* Only compatible with **PHP 8.4.7 TS x64 VC17** builds.

## 📄 License

This DLL was built from the original [phpredis source](https://github.com/phpredis/phpredis), which is released under the [BSD-3-Clause License](https://opensource.org/licenses/BSD-3-Clause).

> All rights belong to the original authors.
