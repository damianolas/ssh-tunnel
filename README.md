# Info

Il file config torna utile quando si vuole accedere a un server privato, sfruttando un tunnel SSH che passa per la bastion instance in subnet pubblica.

Il file config deve essere allocato in ~/.ssh/, quindi ``` sudo vim ~/.ssh/config ``` e incollare

Impostare i permessi sulla .pem ``` sudo chmod 400 <path_chiave.pem> ```

Si accede alla macchina privata con ``` ssh serverPippo ```
