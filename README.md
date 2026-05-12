# Auditoria-ASG-y-Refactorizacion-Sostenible
María Dolores Barba y Antonio Muñoz

## Introducción

Nuestra elección ha sido la empresa sevillana Bernardo Herrera S.L. Esto se debe a que es una empresa que conocemos de cerca y de la cuál tenemos contactos. Hemos analizado su página web y consideramos que carece de contenidos indispensables para el funcionamiento de una página a nivel empresarial, hecho que ha reforzado nuestra elección y nos ha dado ideas sobre posibles nuevas funcionalidades para añadir a esta respetando que sea un código sostenible. 

## Fase 1: Inventario y Dimensión Ambiental (A)

La primera tarea que llevamos a cabo fue la medición de la huella de carbono de la página. Para ello, entramos en la página Website Carbon Calculator para hacer la medición. Tras introducir la URL, nos devolvió lo siguiente: <img width="796" height="401" alt="image" src="https://github.com/user-attachments/assets/b657751c-c04a-4e63-9673-d5bde03ec72f" />
Con esto, concluimos que aunque la página web no sea muy "sucia", existen varios apartados en los que puede mejorar considerablemente. 

Los tres recursos que más provocan un bajo rendimiento en la web es la implementacion de JavaScript que no se usa junto al mismo problema con CSS. Además, tiene un tiempo de carga superior a 2,8 segundos debido a la sobrecarga de elementos en el hilo principal. Analizando las métricas, el primer conteo de impresión es de 1 segundo, el tiempo de bloqueo es de 530ms y la velocidad del index es de 3.1s, todo esto para ordenador. 
Para móvil, las mediciones son diferentes. El rendimiento es algo mejor, pero el primer conteo de impresión aumenta a 2.6s, por el contrario, el tiempo de bloqueo es 0. Por último, la velocidad de index aumenta a 2.8s. Aunque algunas de las métricas aumenten, el rendimiento general aumenta de 64 a 80. Por esto, consideramos que las principales mejoras se tienen que llevar a cabo en la versión de ordenador.

<img width="533" height="169" alt="image" src="https://github.com/user-attachments/assets/ef13b402-f519-48c2-b547-b1d77fe4784f" />


