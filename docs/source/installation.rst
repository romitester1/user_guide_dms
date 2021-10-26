Instalasi dan implementasi
==========================

Aplikasi ini menggunakan teknologi web, ini berarti aplikasi menggunakan peramban web untuk mengaksesnya, menggunakan database MySQL sebagai mesin penyimpanan data, menggunakan bahasa pemrograman PHP yang disimpan di satu mesin server secara terpusat. Aplikasi ini optimum diakses oleh peramban web Mozilla Firefox, Google Chrome, Safari versi terakhir.

System Requirement
------------------

+----+-------------+--------------------+--------------------------------------------------------------------------------+
| No | Server Role | Item               | Detail                                                                         |
|    |             |                    |                                                                                |
+====+=============+====================+================================================================================+
| 1  | Database    | O/S                | Debian Linux (Ubuntu Server 12.04 LTS)                                         |
+----+-------------+--------------------+--------------------------------------------------------------------------------+
|    |             | Database           | MySQL Server                                                                   |
+----+-------------+--------------------+--------------------------------------------------------------------------------+
|    |             | Collation database | Oracle Server                                                                  |
+----+-------------+--------------------+--------------------------------------------------------------------------------+
|    |             | Framework          | none                                                                           |
+----+-------------+--------------------+--------------------------------------------------------------------------------+
| 2  | Application | O/S                | Debian Linux (Ubuntu Server 12.04 LTS)                                         |
+----+-------------+--------------------+--------------------------------------------------------------------------------+
|    |             | Framework          | Native PHP                                                                     |
+----+-------------+--------------------+--------------------------------------------------------------------------------+
|    |             | Other Detail       | Menggunakan bahasa pemrograman pendukung seperti: JS, CSS, jQuery & HTML5      |
+----+-------------+--------------------+--------------------------------------------------------------------------------+
| 3  | Web Server  | O/S                | Debian Linux (Ubuntu Server 12.04 LTS)                                         |
+----+-------------+--------------------+--------------------------------------------------------------------------------+
|    |             | Framework          | Apache2, MySQL Server, PHP5, PHPMyAdmin                                        |
+----+-------------+--------------------+--------------------------------------------------------------------------------+
|    |             | Other Detail       | Menggunakan library pendukung untuk membuat aplikasi berjalan secara powerfull |
+----+-------------+--------------------+--------------------------------------------------------------------------------+


User & Role
-----------

User-user yang akan terlibat di dalam pengoperasian sistem DMS dan Nota Dinas Adhikarya ini akan memiliki peran, yang secara garis besar terbagi atas 4 role utama sebagai berikut :

.. admonition:: Normal User
    
   Pengguna biasa, yang dapat diatur hak aksesnya sesuai kewenangan user tersebut di dalam sebuah department / divisi.

.. admonition:: Department Admin
    
   User-user yang diberikan wewenang oleh super admin untuk mengatur hak akses folder, dokumen, dan para user yang berada di dalam department / divisi tertentu.

.. admonition:: Super Admin
    
   User yang memiliki kewenangan tertinggi di dalam sistem, yang dapat melakukan konfigurasi dan menentukan setting sistem pada level advance.

.. admonition:: Management
    
   User level Managerial (Direksi / GM / ManagerBiro / Komisaris).

.. admonition:: Drafter
    
   Pembuat Surat   

.. admonition:: Reviewer
    
   Peninjau


Penggunaan Pertama
------------------

Karena aplikasi ini berbasis web, Anda tidak perlu menginstall aplikasi ini di PC/laptop. Aplikasi ini dapat diakses langsung dengan memanfaatkan aplikasi peramban web (browser) seperti Mozilla Firefox, Google Chrome, Safari atau Microsoft Internet Explorer versi terbaru. Setelah masuk ke peramban web, silahkan masuk ke URL yang disediakan.

Setelah masuk ke halaman login, silahkan masuk dengan menggunakan alamat email korporat dan password Anda. Untuk selanjutnya, proses pendaftaran user baru dapat menghubungi administrator di departemen masing-masing.
