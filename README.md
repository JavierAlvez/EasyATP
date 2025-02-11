# EasyATP

Urratsak:

1. Saio berri bat ireki zure github.com kontuan, edo sortu kontu berri bat. 

2. Erabili zure edozein biltegi (repository), edo sortu biltegi berri bat.

    2a. ![Create a new repository](https://github.com/JavierAlvez/EasyATP/blob/main/images/CreateNewCodespace.png)
    
    2b. ![Set new repository name](https://github.com/JavierAlvez/EasyATP/blob/main/images/CreateNewRepositorySetName.png)
    
    2c. ![Save new repository](https://github.com/JavierAlvez/EasyATP/blob/main/images/CreateNewRepositorySaveButton.png)

3. Sortu codespace berri bat. Zure biltegia hutsa bada (berria), JavierAlvez/EasyATP biltegia (honako hau) klonatu ahal duzu:

    3a. ![Create a new codespace](https://github.com/JavierAlvez/EasyATP/blob/main/images/CreateNewCodespace.png)
    
    3b. ![Select a non-empty repository](https://github.com/JavierAlvez/EasyATP/blob/main/images/CreateNewCodespaceSelectRepository.png)
    
    3c. ![Save new repository](https://github.com/JavierAlvez/EasyATP/blob/main/images/CreateNewCodespaceCreateButton.png)

4. Terminal lehioan exekutatu hurrengo komandoa:

```bash
docker run --name easyatp -p 3000:3000 -d javieralvez/easyatp:2024
```

5. Bukatzeko, lan egin eta gero, terminal lehioan exekutatu hurrengo komandoa:

```bash
docker stop easyatp
```

