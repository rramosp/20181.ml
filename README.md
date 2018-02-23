# 2018/1 Machine Learning

## 2018 - Semestre I - Universidad Industrial de Santander

_Regístrate [aquí](https://docs.google.com/forms/d/e/1FAIpQLSekLcDmMN8n2o4U5wmaXK4wpcK-EqaAW2atfWFiTVO_5dM-kQ/viewform)_



## Reference MOOCs

- [EDX Machine Learning Fundamentals UCSanDiegoX: DSE220x](https://courses.edx.org/courses/course-v1:UCSanDiegoX+DS220x+1T2018/course/) 10 semanas
- [UDACITY Google Deep Learning Course](https://classroom.udacity.com/courses/ud730) 7 lecciones

### Entregas parciales reference MOOC

                       Curso EDX         Curso UDACITY
    Entrega 1, Mar 30: Semanas 1,2,3     Lecciones 1,2
    Entrega 2, Abr 27: Semanas 4,5,6     Lecciones 3,4,5
    Entrega 3, May 27: Semanas 7,8,9,10  Lecciones 6,7,8

    Mar09 - Registro primera calificación
    Mar11 - Último día cancelación materias
    May28-Jun06 Evaluaciones finales
    Jun08 - Registro calificaciones finales

### Instrucciones entregas parciales

- Las entregas se realizarán en el Dropbox compartido con cada alumno
- Cada entrega deberá de constar de:

  - un archivo **en formato PDF** llamado **EDX_01.PDF** o **UDACITY_01.PDF** según el curso que hayas escogido (edx_02.pdf para la entrega 2, etc.) con la evidencia de la realización de la parte correspondiente del MOOC (pantallazos, resúmenes, calificaciones, etc.)
  - un archivo **en formato ZIP** llamado **EDX_01.ZIP** o **UDACITY_01.ZIP** (edx_02.zip, etc.) con los materiales que tuviste que desarrollar durante las lecciones correspondientes a la entrega (código, binarios, docs, etc.)

- En cada entrega se valorará:

  - 50% COMPLETUD, si la entrega contiene todas las lecciones requeridas
  - 50% CLARIDAD, si el PDF describe claramente lo realizado complementando con explicación del estudiante los pantallazos y evidencia incluida en el mismo, y si el ZIP contiene los materiales de manera organizada (en directorios, READMEs, etc.)

### Calificación del curso

    Problemsets 1 2 3    15%
    Quiz 1               10%
    MOOC Entrega 1       25%
    MOOC Entrega 2       25%
    MOOC Entrega 3       25%
  
  
---
# Programación original del curso

## Máquina Virtual

Usaremos esta máquina virtual que tiene instalado un entorno Python Anaconda con Jupyter Notebooks disponibles en  [localhost:8008/tree](http://localhost:8008/tree) una vez que la máquina arranca.

**Observa la configuración de la máquina**

- Si tu máquina física tiene al menos 4GB de memoria configura la máquina virtual **con 2GB de memoria**
- Aunque casi no necesitarás un terminal, el interfaz de Jupyter Notebooks tiene un terminal para acceder a través del navegador. En cualquier caso, la máquina virtual tiene un servidor SSH en el puerto 2222 con user/user como usuario y pwd. Si tu máquina física es mac o linux usa `ssh -p 2222 user@localhost` para conectarte. Si es windows, usa [putty](https://www.putty.org/)
- Si compartes una carpeta entre la física y virtual asegúrate que **el nombre cone el que se comparte** sea `share` (aunque el nombre de la carpeta en la máquina física puede ser distinto)

**Para montar la carpeta compartida** ejecuta lo siguiente en un terminal y la carpeta aparecerá en /home/user/share:

    sudo mount share

**Si la máquina arranca en modo mantenimiento**, edita el fichero `/etc/fstab` como `root`:

    sudo nano /etc/fstab
    
y actualiza la linea con la definición de `share` para que quede así

    share                                     /home/user/share vboxsf uid=1000,rw,auto,x-systemd.automount 0 1


### Calificación

40% Problemsets<br/>
30% Quizes<br/>
30% Data analytics project

### Contenidos

1. Mathematical optimization and symbolic computing
2. Linear Regression
3. Logistic Regression
4. Neural Networks
5. Regularization and performance evaluation
6. Kernel methods
7. Ensemble methods
8. Learning representations
9. Deep learning

### Data analytics project

Deberás de abordar un problema de analítica de datos, 1) elegir dataset, 2) definir tarea, 3) implementar la analítica de datos. El resultado ha de ser un notebook ejecutable que contenga, preprocesado (latent semantics y/o transformaciones), varios algoritmos de clasificación o regresión, análisis de rendimiento y curvas de aprendizaje.

Hay muchas fuentes de datos y sitios de competiciones de machine learning en internet, entre ellas: [kaggle](https://www.kaggle.com/competitions), [kdnudgets](http://www.kdnuggets.com/competitions/) 

Criterios de evaluación: 1) Complejidad de la tarea, 2) Compleción 3) Claridad del notebook

### Programa y fechas

                       SESSION 1     SESSION 2     STUDENT DEADLINES
    W05 Ene29-Feb02    INTRO         1.MATH
    W06 Feb05-Feb09    2.LINREG      PSETS
    W07 Feb12-Feb16    3.LOGREG      PSETS         
    W08 Feb19-Feb23    PROJECT       PROJECT       Feb 25 PSETS 1 2 3
    W09 Feb26-Mar02    QUIZPREP      QUIZ         Mar 04 PROJECT DATASET
    W10 Mar05-Mar09    4.NEURAL      PSETS
    W11 Mar12-Mar16    5.REGPE       PSETS
    W12 Mar19-Mar23    PROJECT       PROJECT
    W13 Mar26-Mar30    6.LATSEM      PSETS         Abr 01 PSETS 4 5 6
    W14 Abr02-Abr06    QUIZPREP      QUIZ
    W15 Abr09-Abr13    PROJECT       PROJECT
    W16 Abr16-Abr20    7.KERNEL      PSETS
    W17 Abr23-Abr27    8.ENSEMBL     PSETS
    W18 Abr30-May04    9.CNN+RNN     PSETS         MAY 06 PSETS 7 8 9
    W19 May07-May11    QUIZPREP      QUIZ
    W20 May14-May18    PROJECT       PROJECT
    W21 May21-May25    SEMINAR       SEMINAR       MAY 27 PROJECT FINAL


    Mar09 - Registro primera calificación
    Mar11 - Último día cancelación materias
    May28-Jun06 Evaluaciones finales
    Jun08 - Registro calificaciones finales

