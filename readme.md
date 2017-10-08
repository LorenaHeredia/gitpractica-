**1.	¿Qué comando utilizaste en el paso 11? ¿Por qué?**
git reset --hard HEAD~1. 
Porque con este comando se elimina el último commit (~1) eliminand lo que había en el working copy.

**2.	¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?**
git reflog 
git reset --hard c4619ac
Utilizo git reflog para ver el historial de los commits y luego aplico el identificador del commit que quiero rehacer con el git reset --hard para reestablecerlo.

**3.	El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?**
No causó ningún conflicto porque la rama styled era la última que estaba modificada y master absorbió esos cambios, que era aplicar el estilo de letra.

**4.	El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?**
Si causo conflicto porque styled y htmlify eran  textos diferentes, y el programa no sabía cuál tenía que definir.

**5. El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?**
No causo ningún conflicto, la rama master aplicó los cambios de la rama styled.

**6. ¿Qué comando o comandos utilizaste en el paso 25?**
git graph

**7. El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?**
Sí, porque las dos ramas están en la misma línea.

**8. ¿Qué comando o comandos utilizaste en el paso 27?**
git reset HEAD~1

**9. ¿Qué comando o comandos utilizaste en el paso 28?**
git reset HEAD

**10. ¿Qué comando o comandos utilizaste en el paso 29?**
git branch –D title

**11. ¿Qué comando o comandos utilizaste en el paso 30?**
git reflog
git reset --hard b665225

**12. ¿Qué comando o comandos usaste en el paso 32?**
git reflog
git checkout 35037f0


**13. ¿Qué comando o comandos usaste en el punto 33?**
git reflog
git checkout b665225

