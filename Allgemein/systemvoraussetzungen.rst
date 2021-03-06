Systemvoraussetzungen
#####################
:date: 2014-09-04 13:23
:author: admin
:category: Allgemein
:slug: systemvoraussetzungen
:status: published

Systemvoraussetzungen
~~~~~~~~~~~~~~~~~~~~~

-  Apache2
-  MySQL 5
-  PHP 7.2, 7.3
-  JSON
-  ctype
-  SOAP
-  date.timezone in der php.ini gesetzt
-  Ioncube loader
-  CURL
-  PHP exec Funktion erlaubt und folgende Programme erlaubt und im $PATH verfügbar: mysqldump, wget, unzip, rm, grep
-  `Libreoffice <https://de.libreoffice.org/>`__ (Server Installation)
-  Ausgehende FTP via TLS Verbindung (FTPS) um Bilder zwischen Warexo und Webshop zu übertragen (nur passive FTPS erlaubt!)
   Eine Übertragung via SFTP ist aus performance Gründen nicht ratsam, wir arbeiten an einer optionalen Unterstützung.
-  SSL-Zertifikat auf dem Server (z.B. Lets Encrypt).

Empfohlene Einstellungen
~~~~~~~~~~~~~~~~~~~~~~~~

-  Sie sollten das PHP-XML Modul installiert haben
-  Sie sollten mindestens version 2.6.21 von libxml haben
-  PHP tokenizer sollte aktiviert sein
-  mbstring Funktionen sollten aktiviert sein
-  iconv sollte aktiviert sein
-  POSIX sollte aktiviert sein (nur für \*nix Systeme)
-  Intl sollte installiert sein mit ICU 4+
-  APC 3.0.17+ (oder ein anderer opcode cache)
-  php.ini Einstellungen

   -  short_open_tag = Off
   -  magic_quotes_gpc = Off
   -  register_globals = Off
   -  session.auto_start = Off

PHP Beschränkungen
~~~~~~~~~~~~~~~~~~

Warexo wird nur für PHP 7.2 und höher unterstützt.
