TP Introducción a Arquitectura - Diagrama de Despliegue
=======================================================

**Rueditas Amigas** es una empresa dedicada a brindar servicios de traslado inclusivos para personas con necesidades específicas. La organización ofrece diferentes tipos de servicios adaptados, tales como traslados turísticos y actividades recreativas, garantizando recorridos de ida y vuelta, dejando a los pasajeros, en el mismo punto de encuentro que en la salida.

Parte de nuestro equipo realizó previamente el modelo de datos y definió un esquema relacional para persistir la información del sistema (ver modelo en el siguiente [link](https://docs.google.com/document/d/1vDZ-ybIgk7lBvqI5vZ0lp2qpSolJnpKDtUftYn65XU8/edit?usp=sharing)).

A partir de este modelo, tenemos que definir una primera versión del sistema que debe cumplir los siguientes requerimientos.


## 📋✏️ Requerimientos

* Las personas **solicitantes** de traslados deben poder ingresar al sistema desde cualquier dispositivo (computadora de escritorio, teléfono celular, etc).a través de **internet**.
* Las personas **solicitantes** podrán ingresar al sistema en cualquier momento del día y realizar su solicitud.
* Las personas **administradoras** del sistema también podrán ingresar al mismo en cualquier horario del día y a través de cualquier dispositivo conectado a **internet** para consultar estadísticas.

**Proponé y diagramá** una arquitectura que resuelva estas problemáticas usando PlantUML.


## 📍 Como resolver el ejercicio

> [!IMPORTANT]
>
> El objetivo del TP no es realizar un diagrama complejo ni con el máximo nivel de detalle posible, sino bosquejar los elementos mínimos de la arquitectura
> física más sencilla que resuelva el problema planteado.

1. Escribí un diagrama de despliegue utilizando [PlantUML](https://plantuml.com/).
2. Guardá tu diagrama como un archivo `.puml` dentro del directorio `diagrams`. El mismo debe verse aproximadamente así:

```bash
$ cat diagrams/diagramaDeEjemplo.puml
@startuml
...
@enduml
```

3. Hacé un _commit_ y _push_ del repositorio tantas veces como necesites.
4. Cuando hayas llegado a la versión final de tu diagrama, creá un tag llamado `entrega-final`:

```bash
git tag entrega-final && git push origin HEAD --tags
```

5. En caso de desear reentregar (siempre que te encuentres dentro del período de envío del trabajo práctico), deberás volver a crear **el mismo** tag:

```bash
git tag -f entrega-final && git push origin HEAD --tags -f
```

Una vez que hayan entregado satisfactoriamente, deberán ver un tilde verde en su último commit:

<img width="875" height="81" alt="image" src="https://github.com/user-attachments/assets/e497b30e-3f14-482d-b9df-855ba64512c9" />


## 🔗 Materiales útiles

Este ejercicio se puede resolver íntegramente con los contenidos vistos en la primera clase de arquitectura. A modo de repaso y profundización, de todas formas, dejamos los siguientes enlaces:

* 📄 [EntregaYaYaYa de la Guía de ejercicios de Arquitectura](https://docs.google.com/document/d/1snIOX5rNp3kwEkWF3R04-KuujUbMTOz1wanl3Rut0Ts/edit?tab=t.0#heading=h.tvlfd8lfshb0)
* 📄 [Introducción a la Arquitectura de Software](https://docs.google.com/document/d/1XaKMrWPA0jntDK29gtEDRw-CoQgWXfHOmdbmihg4MpE/edit?tab=t.0#heading=h.z9jwy1eurzt9)
* 📄 [Introducción a la Arquitectura Web](https://docs.google.com/document/d/1LBqAhXPzn-aeN5BIRZBmIrU5RKiYvySyWH-2Jkn-kJw/edit?tab=t.0)
* 📄 [Documentación de Diagramas de Despliegue en PlantUML](https://plantuml.com/es/deployment-diagram)
* 📄 [Enunciado](https://docs.google.com/document/d/13znCErQxKCfgXqUbEf6sdK3ThnOqYVKeDoQRm6U8J6g/edit?tab=t.0)
* 📄 [Modelo de Datos Relacional](https://docs.google.com/document/d/1vDZ-ybIgk7lBvqI5vZ0lp2qpSolJnpKDtUftYn65XU8/edit?usp=sharing)
