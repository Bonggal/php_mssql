# MS SQL Server Driver for PHP
</br>
1. Run the installation.</br>
2. Copy driver into "xampp/php/ext" folder. </br>
Copy the driver that match with your php version. 
You can check the version from php info using code in "php.php".
Also check the PHP Extension Build from that code and find the driver that match with your PHP extensiob build (e.g. NTS ot TS).</br>
3. Copy the file name of the driver into "\xampp\php\php.ini" (from "Loaded configuration file").
Put into below of "[ExtensionList]", e.g. "extension=php_pdo_sqlsrv_53nts.dll".</br>
4. Check "pdo_sqlsrv" in php info ("php.php").

</br></br>
Some installation tutorial videos:
https://youtu.be/tqMZoR-Q-NY
