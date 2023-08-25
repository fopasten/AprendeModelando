# AprendeModelando
Repositorio creado como recurso de aprendizaje en apoyo al libro Aprende Modelando de Daniel Morillo Torres, Ph.D. y Gustavo Gatica, Ph.D.

## Nota importante

Gurobi se puede utilizar en los cuadernos de Google Colab con la licencia de prueba limitada en tamaño que se instala de forma predeterminada o con una licencia del Servicio de Licencias Web (WLS) que habilita todas las funciones de Gurobi. Cuando se instala a través de pip, gurobipy viene con una licencia de prueba limitada en tamaño que puede resolver modelos con un máximo de 2000 variables y 2000 restricciones. El ejercicio 13 de la parte "Hard" sobrepasa estos requerimientos por lo tanto para hacer pruebas o cambios con ese modelo deberás generar una licencia y aplicarla en entorno local o en Colab. 

## Como obtener licencia Gurobi?

Para obtener una licencia de Gurobi para estudiantes, sigue estos pasos:

1. Regístrate en el [sitio web de Gurobi](https://www.gurobi.com/academia/academic-program-and-licenses/)
2. Selecciona "Académico" cuando se te solicite.
3. Ingresa tu nombre, universidad y país en el formulario y envíalo haciendo clic en "Acceder ahora".
4. Recibirás un correo electrónico que te permitirá establecer una contraseña para tu cuenta en el sitio web de Gurobi.
5. Una vez que hayas iniciado sesión, puedes acceder al [menú de licencias](https://portal.gurobi.com/iam/licenses/request) y seleccionar "request".

Hay varios tipos de licencias disponibles para usuarios académicos, las relevantes en este caso son:
- Licencias académicas individuales con nombre de usuario: Esta es una licencia ilimitada de Gurobi Optimizer para una sola persona, [en una sola máquina](https://support.gurobi.com/hc/en-us/articles/4534601245713-How-do-I-get-started-with-Gurobi-for-academic-users-).
- [Licencias WLS](https://support.gurobi.com/hc/en-us/articles/4534601245713-How-do-I-get-started-with-Gurobi-for-academic-users-): Ejecuta Gurobi Optimizer donde quieras, en entornos contenedorizados o máquinas regulares.

La primera es recomendable usarla para instalar en un computador personal y la segunda es recomendable en el caso de que utilicen Google Colab.

Para generar licencias es requerido estar conectado a la red institucional, es decir debes estar en un computador de la Universidad o conectado vía WiFi/Ethernet.

Al generar licencias se verán de la siguiente forma

![image](https://github.com/fopasten/AprendeModelando/assets/20798216/818713b9-be98-47b6-8e80-216af74b6e4c)


### 1 [Licencia WLS](https://support.gurobi.com/hc/en-us/articles/4409582394769-Google-Colab-Installation-and-Licensing)

Al generar la licencia WLS te dará la opción "Open"

Ahi se detalla el uso de la licencia, permite 2 sesiones activas y dura 90 días que son extendibles mientras permanezcas en la universidad.

![image](https://github.com/fopasten/AprendeModelando/assets/20798216/b92baca1-a53a-45c5-bb7e-e55d92a27afd)

Si das clic en "Download" te permitirá generar un API Key 

![image](https://github.com/fopasten/AprendeModelando/assets/20798216/70b8bc90-ae66-458a-b120-ebf38a5ea38c)

![image](https://github.com/fopasten/AprendeModelando/assets/20798216/7913ee8a-6233-49e2-b1cb-7c0a890a0b4f)

Si descargas los contenidos te entregará un archivo gurobi.lic con el que debes inicializar el ambiente.

### 2 Licencia individual

La instalación en maquinas personales es sencilla, al dar clic en "Install" podrás ver las instrucciones:

![image](https://github.com/fopasten/AprendeModelando/assets/20798216/1be979eb-9728-4d12-a69b-bfe5bba97844)

1. Instalar gurobi
2. Utilizar el comando generado en la consola/terminal para activar la licencia en ese computador.


