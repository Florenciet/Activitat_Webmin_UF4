# Activitat_Webmin_UF4
Activitat UF4 de Webmin fet per Oriol Florencio Pujol i Ayoub Bel Khaddar

## Activitat 1 - Crear i modificar usuaris
- Has de crear dos usuaris bakalao_X i techno_X on (X és el vostre cognom).

![image](https://github.com/user-attachments/assets/b88ee601-a31d-4bbe-9023-42f67c431f89)

![image](https://github.com/user-attachments/assets/05c0d42a-54ec-40a6-8765-61ef0f05f0ed)

- Els usuaris et passaran el hash de la seva contrasenya, no la contrasenya real. (podeu fer servir openssl).

1. Contrasenya de bakalao_florencio --> 12345

![image](https://github.com/user-attachments/assets/7cfcbe80-e32c-4e6d-a718-dda04637109a)

2. Contrasenya de techno_belkhaddar --> 98765

![image](https://github.com/user-attachments/assets/d3c67662-ee0c-4949-ad59-46bf70df1114)

- Cada usuari tindrà un directori a home igual al seu nom d'usuari.

![image](https://github.com/user-attachments/assets/baf2fc59-47ee-4752-bf11-5858f65a3926)

- Utilitzaran bash com a shell.

![image](https://github.com/user-attachments/assets/c7f791e1-4dd7-4fe0-9334-12a084d7c751)

- Els usuaris estaran dins del grup que tingui el seu mateix nom i dins del grup usuaris_empresa.

![image](https://github.com/user-attachments/assets/3a9ce4e4-6bc5-4823-ace8-92f0094c8b9a)

![image](https://github.com/user-attachments/assets/f8cb6dd1-e7ec-4e93-a332-d0da7c139e4a)

![image](https://github.com/user-attachments/assets/48a7aba3-011a-4ce6-8d72-7588cd1bd155)

- L'usuari techno no podrà fer login després del dia 31-03-2025.

![image](https://github.com/user-attachments/assets/bbd677db-7f35-44c6-a6c2-f38bc7a9c655)

- Comproveu que els usuaris poden iniciar sessió.

![image](https://github.com/user-attachments/assets/fca43434-a004-4e94-96db-fb680b57f445)

## Activitat 2 - Programar tasques

- Programa una tasca que neteja els paquets de Linux que ja no s'utilitzen una vegada al mes.

![image](https://github.com/user-attachments/assets/0f7b2615-b4bd-484e-8d9e-ac601913c0cd)

- Programa una tasca diaria que apaga l'ordinador a les 14:00.

![image](https://github.com/user-attachments/assets/2ff63c24-2435-4c30-a8fb-3dfa0ce5dcc6)

## Activitat 3 - Instal·lació de software

- Utilitza webmin per mostrar quins paquets de software es podrien actualitzar.

![image](https://github.com/user-attachments/assets/c5fdc3f0-3a9a-4f31-a2fd-c2d1523cc0c0)

- Des de webmin actualitza un paquet.

![image](https://github.com/user-attachments/assets/408d30b9-8074-4fd0-86b1-d346cde8f29a)

- Utilitza webmin per instal·lar un joc de apt.

![image](https://github.com/user-attachments/assets/00e50e41-2c29-4f16-a472-1cdffcfa77f1)

![image](https://github.com/user-attachments/assets/6eb5c1e3-fe04-4ff7-8525-8c73a4fe4b4b)

- Utilitza webmin per instal·lar gimp de apt.

![image](https://github.com/user-attachments/assets/0e7e9a72-7af4-4119-b478-ffc3a5b2af7f)

## Activitat 4 - Serveis

- Utilitza webmin per mostrar els serveis que s'inicien amb el sistema.

![image](https://github.com/user-attachments/assets/f7992973-a68f-48fb-9d7a-7ad4df8c9369)

- Utilitza webmin per mostrar l'estat del servidor Apache.

![image](https://github.com/user-attachments/assets/ac84423b-00a7-43a6-9f81-35723edd7c0c)

- Utilitza webmin per aturar Apache.

![image](https://github.com/user-attachments/assets/49749e1f-3b0a-4ea3-9945-fefa99a84644)

- Utilitza webmin per mostrar l'estat del servidor Apache apagat.

![image](https://github.com/user-attachments/assets/a9805843-313c-44b5-ba44-5791bbadfc9b)

## Activitat 6 - Còpies de seguretat

- Utilitzant el mòdul de Webmin Filesystem Backup fes una còpia de seguretat del directori /home al directori /backups (l'haureu de crear si no existeix).

![image](https://github.com/user-attachments/assets/de258689-3c58-4e9e-ab2b-8ef45f5069d0)

- Modifica alguns fitxers de /home.

![image](https://github.com/user-attachments/assets/99bb9a10-a68e-4136-b201-2db02a91ddd4)

- Recupera la còpia de seguretat.

![image](https://github.com/user-attachments/assets/1204e984-cb6e-4ec1-9ed7-d749f8e42c6e)

- Comprova que els fitxers de /home són els correctes.

![image](https://github.com/user-attachments/assets/4dcc0c0c-f16f-4190-a5b1-8932d3129a28)

- Programa una còpia de seguretat de /home/bakalao_X per els divendres a les 21:00.

![image](https://github.com/user-attachments/assets/71d8e3ff-2da9-4891-a049-40d5719eca7b)

- Esborra la còpia de seguretat programada anteriorment.

![image](https://github.com/user-attachments/assets/e26b8e43-3299-48bc-9f7c-cda2907c443b)

![image](https://github.com/user-attachments/assets/92f92dc3-d777-40e4-8c0a-4162d4b1b549)































