---
machine_translated: true
machine_translated_rev: d734a8e46ddd7465886ba4133bff743c55190626
toc_priority: 31
toc_title: "\u062A\u0646\u0628\u0644"
---

# تنبل {#lazy}

نگه می دارد جداول در رم تنها `expiration_time_in_seconds` ثانیه پس از دسترسی گذشته. را می توان تنها با استفاده \*جداول ورود به سیستم.

این برای ذخیره سازی بسیاری از جداول کوچک \*ورود به سیستم بهینه شده است که فاصله زمانی طولانی بین دسترسی ها وجود دارد.

## ایجاد یک پایگاه داده {#creating-a-database}

    CREATE DATABASE testlazy ENGINE = Lazy(expiration_time_in_seconds);

[مقاله اصلی](https://clickhouse.tech/docs/en/database_engines/lazy/) <!--hide-->
