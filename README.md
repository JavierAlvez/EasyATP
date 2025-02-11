# EasyATP

## Urratsak:

1. Saio berri bat ireki zure github.com kontuan, edo sortu kontu berri bat. 

2. Erabili zure edozein biltegi (repository), edo sortu biltegi berri bat.

    ![2a. Create a new repository](/images/CreateNewCodespace.png)
    
    ![2b. Set new repository name](/images/CreateNewRepositorySetName.png)
    
    ![2c. Save new repository](/images/CreateNewRepositorySaveButton.png)

3. Sortu codespace berri bat. Zure biltegia hutsa bada (berria), JavierAlvez/EasyATP biltegia (honako hau) klonatu ahal duzu:

    ![2a. Create a new codespace](/images/CreateNewCodespace.png)
    
    ![2b. Select a non-empty repository](/images/CreateNewCodespaceSelectRepository.png)
    
    ![2c. Save new repository](/images/CreateNewCodespaceCreateButton.png)

4. Terminal lehioan exekutatu hurrengo komandoa:

```bash
docker run --name easyatp -p 3000:3000 -d javieralvez/easyatp:2024
```

5. Bukatzeko, lan egin eta gero, terminal lehioan exekutatu hurrengo komandoa:

```bash
docker stop easyatp
```

