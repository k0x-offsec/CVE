# CVE

This repository contains documented CVEs discovered during ethical hacking and security assessments.

| Vulnerability Type       | CVE ID        | Description                                                |
|--------------------------|---------------|------------------------------------------------------------|
| Cross-Site Scripting (XSS) | CVE-2024-8750 | Cross-site Scripting (XSS) vulnerability in idoit pro version 28. This vulnerability allows an attacker to retrieve session details of an authenticated user due to lack of proper sanitization of the following parameters (id,lang,mNavID,name,pID,treeNode,type,view). |
| SQL Injection (SQLi)      | CVE-2024-8749 | Vulnerabilidad de inyección SQL en idoit pro versión 28. Esta vulnerabilidad podría permitir a un atacante enviar una consulta especialmente manipulada al parámetro ID en /var/www/html/src/classes/modules/api/model/cmdb/isys_api_model_cmdb_objects_by_relation.class.php y recuperar toda la información almacenada en la base de datos. |
