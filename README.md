[Disk Usage Reports](http://diskusagereports.com/)
==================

Even in a world of cheap storage, sometimes disk usage means a lot.
Backups can take forever and unnecessarily large files can eat up bandwidth.
Disk Usage Reports provides you with rich web-based usage reports to help keep things under control.

Get started at http://diskusagereports.com!

Quick Start
-----------

1.  Download the latest version at http://diskusagereports.com/download.html

2.  Unzip the files into your Web server's public directory:
    
    * Linux: `/usr/local/apache/htdocs` or `/var/www/html` (check your httpd.conf)
    
    * Windows: `C:\Inetpub\wwwroot`

3.  If your web server executes PHP scripts, you must either secure the `scripts` directory so
    it is not publicly accessible, or move the it to a location on your server that is not
    publicly accessible.

4.  Open a console/terminal window and change directory
    (e.g. `cd /usr/local/apache/htdocs/diskusagereports`) to the installation directory.

5.  Make sure PHP is available by executing: `php -v`

6.  Execute one of the following, changing `path/to/directory` to something else:
    
    * Linux: `bash scripts\find.sh path/to/directory | php scripts\process.php data\myreport`
    
    * Windows: `scripts\find.exe path\to\directory | php scripts\process.php data\myreport`
    
    * Others: `php scripts\find.php path/to/directory | php scripts\process.php data\myreport`
    
7.  Open your browser and visit the following (changing anything before the `?` as necessary):
    
    `http://localhost/diskusagereports/?myreport`

8.  You should be viewing a usage report! If not, get help at http://diskusagereports.com/help/


Getting Help
------------

To get assistance, please contact me at help@diskusagereports.com.

You may also submit issues at https://github.com/amekkawi/diskusagereports/issues (requires free GitHub account).