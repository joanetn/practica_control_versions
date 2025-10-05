# Documentació del Projecte - Control de Versions amb Git Flow

## 1. Introducció

En aquest projecte hem utilitzat **Git**, un sistema de control de versions distribuït que ens permet portar un seguiment detallat dels canvis en el codi, treballar de manera col·laborativa i recuperar versions anteriors si és necessari.  

A més, hem aplicat la metodologia **Git Flow**, que consisteix en utilitzar branques específiques amb una finalitat clara:  

- `develop`: branca principal de desenvolupament.  
- `feature/...`: branques per implementar noves funcionalitats.  
- `release/...`: branques per preparar versions estables.  
- `hotfix/...`: branques per corregir errors crítics en versions ja publicades.  
- `master` o `main`: branca estable del projecte.  

La utilització de Git Flow ens ha permès treballar de manera ordenada, assignar tasques a diferents usuaris i tenir un historial clar de tots els canvis.

---

## 2. Procés realitzat

### Usuari 1

1. Inicialitza el **Git Flow** al repositori (branques predeterminades).  
   ![Inicialització de Git Flow](images/foto1.png)

2. Comença la **feature `estructura-inicial`** i crea el *boilerplate* en la carpeta del projecte.  
   ![Creació del boilerplate](images/foto2.png)

3. Primer commit per documentar la feature, segon commit amb modificació del `index.html`. Finalitza la feature.  
   ![Commits i finalització de la feature](images/foto3.png)
   ![Commits i finalització de la feature](images/foto4.png)
   ![Commits i finalització de la feature](images/foto5.png)
   ![Commits i finalització de la feature](images/foto6.png)
   ![Commits i finalització de la feature](images/foto7.png)



---

### Usuari 2

1. **Feature `modificar-contingut`**:  
    ![](images/foto8.png)
   - Primer commit: modificació del menú de `index.html` per enllaçar al nou fitxer HTML.  
     ![Primer commit modificar-contingut](images/foto9.png)  
   - Segon commit: creació de `contingut.html` amb el contingut demanat.  
     ![Segon commit modificar-contingut](images/foto10.png)  
     ![Segon commit modificar-contingut](images/foto11.png)  
   - Finalitza la feature.  
     ![Finalització modificar-contingut](images/foto12.png)

2. **Feature `modificar-atributs`**:  
    ![](images/foto13.png)
   - Primer commit: modificació del menú de `index.html`.  
     ![Primer commit modificar-atributs](images/foto14.png)  
   - Segon commit: creació i modificació de `atributs.html`.  
     ![Segon commit modificar-atributs](images/foto15.png)  
     ![Segon commit modificar-atributs](images/foto16.png)  
   - Finalitza la feature.  
     ![Finalització modificar-atributs](images/foto17.png)

> Així és l’estructura del projecte en aquest punt.  
![Estructura després del treball de l’Usuari 2](images/foto18.png)

---

### Usuari 3

1. **Feature `modificar-css`**:  
     ![](images/foto19.png)  
   - Primer commit: modificació del menú de `index.html`.  
     ![Primer commit modificar-css](images/foto20.png)  
   - Segon commit: creació i modificació de `estilsCSS.html`.  
     ![Segon commit modificar-css](images/foto21.png)  
   - Finalitza la feature.  
     ![Finalització modificar-css](images/foto22.png)

2. **Release `v1.0`**: inici i finalització.  
   ![Creació i finalització de la release v1.0](images/foto23.png)
   ![Creació i finalització de la release v1.0](images/foto23.png)
   ![Creació i finalització de la release v1.0](images/foto25.png)
   ![Creació i finalització de la release v1.0](images/foto26.png)

> Estructura del projecte després de la release v1.0  
![Estructura després de la release](images/foto27.png)

---

### Usuari 1 - Hotfix

1. **Hotfix `milloresV_1_0`**:  
   ![](images/foto28.png)
   - Primer commit: modificació de `contingut.html`.  
     ![Primer commit hotfix](images/foto29.png)  
   - Segon commit: modificació de `atributs.html`.  
     ![Segon commit hotfix](images/foto30.png)  
   - Finalitza el hotfix.  
     ![Finalització hotfix](images/foto31.png)

> Estructura final del projecte  
![Estructura final](images/foto32.png)

---

## 3. Conclusió

Amb aquest procés hem pogut veure com **Git Flow organitza el desenvolupament**, permetent treballar de manera col·laborativa, implementar noves funcionalitats en *features*, preparar versions estables amb *releases* i corregir errors amb *hotfixes*.  

La documentació creada a la branca `gh-pages` permet visualitzar tot el procés, incloent els commits, les branques i les captures del treball realitzat.
