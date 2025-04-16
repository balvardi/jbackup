# JBackup - Joomla 5 Backup Component Created By Dima Group

<p align="center">
  <img src="https://raw.githubusercontent.com/balvardi/jbackup/main/assets/jbackup-logo.png" alt="JBackup Logo" width="150">
</p>

<p align="center">
  <a href="#english">English</a> | <a href="#persian">فارسی</a>
</p>

<a name="english"></a>
## Overview

JBackup is a comprehensive backup solution for Joomla 5 websites. This component allows administrators to create, manage, download, and restore backups of their Joomla site with ease. It provides flexible options for backing up files, database, or both, with additional configuration settings to customize the backup process.

## Features

- **Multiple Backup Types**:
  - Full backup (files and database)
  - Files-only backup
  - Database-only backup

- **Advanced Options**:
  - Exclude cache files
  - Exclude log files
  - Exclude temporary files
  - Custom backup naming

- **Backup Management**:
  - List all backups with details (size, date, type)
  - Download backups as ZIP files
  - Restore backups with confirmation
  - Delete unwanted backups

- **Configuration Settings**:
  - Custom backup storage location
  - Backup retention settings
  - Automatic backup scheduling options

- **Security**:
  - Permission-based access control
  - Token verification for sensitive operations

## Requirements

- Joomla 5.x
- PHP 8.0 or higher
- MySQL 5.7 or higher
- ZipArchive PHP extension enabled

## Installation

1. Download the latest release from the [releases page](https://github.com/balvardi/jbackup/releases) or use the ZIP file in this repository
2. Go to Joomla administrator → Extensions → Install
3. Upload and install the ZIP file
4. Access the component from the Components menu → JBackup

## Usage

### Creating a Backup

1. Go to Components → JBackup → Create Backup
2. Enter a name for your backup (or use the default generated name)
3. Select the backup type (Full, Files, or Database)
4. Choose which files to exclude (cache, logs, temporary files)
5. Click "Start Backup" to begin the process
6. Wait for the backup to complete

### Managing Backups

1. Go to Components → JBackup → Backups
2. View the list of all your backups
3. Use the action buttons to:
   - Download a backup
   - Restore a backup
   - Delete a backup

### Restoring a Backup

1. Go to Components → JBackup → Backups
2. Find the backup you want to restore
3. Click the "Restore" button
4. Confirm the restoration process
5. Wait for the process to complete

## Configuration

1. Go to Components → JBackup → Settings
2. Configure the following options:
   - Backup storage directory
   - Number of backups to retain
   - Enable/disable automatic backups
   - Set automatic backup frequency
   - Choose automatic backup type

## Screenshots

*Coming soon*

## Roadmap

- Cloud storage integration (Google Drive, Dropbox, etc.)
- Email notifications for backup status
- Frontend component for user backups
- Backup encryption options
- Multi-site backup support

## Contributing

Contributions are welcome! If you'd like to contribute to this project, please follow these steps:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/your-feature-name`)
3. Make your changes
4. Commit your changes (`git commit -m 'Add some feature'`)
5. Push to the branch (`git push origin feature/your-feature-name`)
6. Open a Pull Request

## License

This project is licensed under the GNU General Public License v2.0 or later - see the [LICENSE](LICENSE) file for details.

---

<a name="persian"></a>
# JBackup - کامپوننت پشتیبان‌گیری جوملا ۵

## نمای کلی

JBackup یک راه‌حل جامع پشتیبان‌گیری برای وب‌سایت‌های جوملا ۵ است. این کامپوننت به مدیران اجازه می‌دهد تا به راحتی از سایت جوملای خود پشتیبان تهیه کنند، آن‌ها را مدیریت کنند، دانلود کنند و در صورت نیاز بازیابی نمایند. این کامپوننت گزینه‌های انعطاف‌پذیری برای پشتیبان‌گیری از فایل‌ها، پایگاه داده یا هر دو، با تنظیمات اضافی برای سفارشی‌سازی فرآیند پشتیبان‌گیری ارائه می‌دهد.

## ویژگی‌ها

- **انواع پشتیبان‌گیری**:
  - پشتیبان‌گیری کامل (فایل‌ها و پایگاه داده)
  - پشتیبان‌گیری فقط از فایل‌ها
  - پشتیبان‌گیری فقط از پایگاه داده

- **گزینه‌های پیشرفته**:
  - حذف فایل‌های کش
  - حذف فایل‌های لاگ
  - حذف فایل‌های موقت
  - نام‌گذاری سفارشی پشتیبان

- **مدیریت پشتیبان‌ها**:
  - لیست تمام پشتیبان‌ها با جزئیات (اندازه، تاریخ، نوع)
  - دانلود پشتیبان‌ها به صورت فایل ZIP
  - بازیابی پشتیبان‌ها با تأیید
  - حذف پشتیبان‌های ناخواسته

- **تنظیمات پیکربندی**:
  - محل ذخیره‌سازی سفارشی پشتیبان
  - تنظیمات نگهداری پشتیبان
  - گزینه‌های زمان‌بندی پشتیبان‌گیری خودکار

- **امنیت**:
  - کنترل دسترسی بر اساس مجوزها
  - تأیید توکن برای عملیات حساس

## نیازمندی‌ها

- جوملا ۵.x
- PHP 8.0 یا بالاتر
- MySQL 5.7 یا بالاتر
- افزونه ZipArchive در PHP فعال باشد

## نصب

1. آخرین نسخه را از [صفحه انتشارها](https://github.com/balvardi/jbackup/releases) دانلود کنید یا از فایل ZIP موجود در این مخزن استفاده کنید
2. به بخش مدیریت جوملا بروید → افزونه‌ها → نصب
3. فایل ZIP را آپلود و نصب کنید
4. به کامپوننت از منوی کامپوننت‌ها → JBackup دسترسی پیدا کنید

## استفاده

### ایجاد پشتیبان

1. به کامپوننت‌ها → JBackup → ایجاد پشتیبان بروید
2. نامی برای پشتیبان خود وارد کنید (یا از نام پیش‌فرض تولید شده استفاده کنید)
3. نوع پشتیبان را انتخاب کنید (کامل، فایل‌ها یا پایگاه داده)
4. انتخاب کنید کدام فایل‌ها حذف شوند (کش، لاگ‌ها، فایل‌های موقت)
5. روی "شروع پشتیبان‌گیری" کلیک کنید تا فرآیند شروع شود
6. منتظر بمانید تا پشتیبان‌گیری کامل شود

### مدیریت پشتیبان‌ها

1. به کامپوننت‌ها → JBackup → پشتیبان‌ها بروید
2. لیست تمام پشتیبان‌های خود را مشاهده کنید
3. از دکمه‌های عملیات استفاده کنید برای:
   - دانلود پشتیبان
   - بازیابی پشتیبان
   - حذف پشتیبان

### بازیابی پشتیبان

1. به کامپوننت‌ها → JBackup → پشتیبان‌ها بروید
2. پشتیبانی که می‌خواهید بازیابی کنید را پیدا کنید
3. روی دکمه "بازیابی" کلیک کنید
4. فرآیند بازیابی را تأیید کنید
5. منتظر بمانید تا فرآیند کامل شود

## پیکربندی

1. به کامپوننت‌ها → JBackup → تنظیمات بروید
2. گزینه‌های زیر را پیکربندی کنید:
   - دایرکتوری ذخیره‌سازی پشتیبان
   - تعداد پشتیبان‌هایی که باید نگهداری شوند
   - فعال/غیرفعال کردن پشتیبان‌گیری خودکار
   - تنظیم فرکانس پشتیبان‌گیری خودکار
   - انتخاب نوع پشتیبان‌گیری خودکار

## تصاویر

*به زودی*

## نقشه راه

- ادغام با فضای ذخیره‌سازی ابری (گوگل درایو، دراپ باکس و غیره)
- اطلاع‌رسانی ایمیلی برای وضعیت پشتیبان‌گیری
- کامپوننت فرانت‌اند برای پشتیبان‌گیری کاربران
- گزینه‌های رمزگذاری پشتیبان
- پشتیبانی از پشتیبان‌گیری چند سایته

## مشارکت

مشارکت‌ها مورد استقبال قرار می‌گیرند! اگر می‌خواهید در این پروژه مشارکت کنید، لطفاً این مراحل را دنبال کنید:

1. مخزن را فورک کنید
2. یک شاخه جدید ایجاد کنید (`git checkout -b feature/your-feature-name`)
3. تغییرات خود را اعمال کنید
4. تغییرات خود را کامیت کنید (`git commit -m 'Add some feature'`)
5. به شاخه پوش کنید (`git push origin feature/your-feature-name`)
6. یک درخواست Pull باز کنید

## مجوز

این پروژه تحت مجوز GNU General Public License v2.0 یا بالاتر منتشر شده است - برای جزئیات به فایل [LICENSE](LICENSE) مراجعه کنید.
```

### Next Steps for Your Repository

Now that I've seen your GitHub repository, here are some suggestions to enhance it:

1. **Add a Logo**: Create a simple logo for JBackup and place it in an `assets` folder in your repository. Update the README to point to this logo.

2. **Create a Release**: Set up an official release for your component with proper versioning (v1.0.0-beta).

3. **Add Screenshots**: Take screenshots of your component in action and add them to the README to help users understand how it works.

4. **Add a LICENSE File**: Add a GNU GPL v2.0 or later license file to your repository.

5. **Create Documentation**: Consider adding more detailed documentation in a `docs` folder.

6. **Set Up Issue Templates**: Add issue templates to help users report bugs or request features in a structured way.

The README I've provided is ready to use and will give your repository a professional appearance while providing comprehensive information about your component.
```

