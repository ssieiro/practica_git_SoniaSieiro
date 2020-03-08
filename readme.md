- ¿Qué comando utilizaste en el paso 11? ¿Por qué?
*Uso el comando <strong>reset --hard HEAD~1</strong> para volver atrás y eliminar lo que haya en el working copy*
- ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?
*Primero compruebo el hash con reflog y luego uso el comando <strong> reset --hard [hash]</strong> para recuperar los cambios*
- El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?
*no, porque el merge no se realiza*
- El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?
*sí, porque el archivo estaba modificado en dos ramas distintas*
- El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?
*no, porque en master no había modificaciones*
- ¿Qué comando o comandos utilizaste en el paso 25?
*utilizo <strong>git graph</strong> que es un alias de el comando <strong>git log --graph --decorate --pretty=oneline</strong>*
- El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?
*Sí, porque solo hay un commit por delante de master*
- ¿Qué comando o comandos utilizaste en el paso 27?
*El comando <strong>git reset HEAD~1</strong> para deshacer el último paso*
- ¿Qué comando o comandos utilizaste en el paso 28?
*<strong>git checkout git-nuestro.md</strong>*
- ¿Qué comando o comandos utilizaste en el paso 29?
*<strong>git branch -D title</strong> para que la elimine aunque haya cambios que no están añadidos*
- ¿Qué comando o comandos utilizaste en el paso 30?
*Compruebo el hash con reflog y uso el comando <strong>git reset --hard [hash]</strong>*
- ¿Qué comando o comandos usaste en el paso 32?
*Compruebo el hash del commit inicial con reflog y uso el comando <strong>git reset --hard [hash]</strong>*
- ¿Qué comando o comandos usaste en el punto 33?
*Compruebo el hash con reflog y uso el comando <strong>git reset --hard [hash]</strong>*

