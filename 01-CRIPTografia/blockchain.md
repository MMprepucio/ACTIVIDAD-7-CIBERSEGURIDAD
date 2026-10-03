# Blockchain y criptografía

## ¿Blockchain es un tipo de criptografía?

No. Blockchain no es un tipo de criptografía. Es una tecnología de registro distribuido que utiliza diferentes técnicas criptográficas para proteger la información, verificar transacciones y mantener la integridad de los datos.

La criptografía es una de las tecnologías que permite que una blockchain funcione de forma segura.

## ¿Qué es Blockchain?

Blockchain es una tecnología que permite almacenar información en una cadena de bloques. Cada bloque contiene información y está relacionado criptográficamente con el bloque anterior.

La información se almacena en diferentes computadores o nodos de una red, lo que permite mantener un registro distribuido.

## Características principales

- **Descentralización:** la información puede mantenerse en una red de diferentes nodos.
- **Integridad:** los mecanismos criptográficos ayudan a detectar modificaciones en los datos.
- **Transparencia:** dependiendo del tipo de blockchain, las transacciones pueden ser consultadas por los participantes de la red.
- **Inmutabilidad:** modificar información de bloques anteriores puede ser muy difícil debido a la estructura de la cadena y los mecanismos de seguridad.
- **Trazabilidad:** permite seguir el registro de las operaciones almacenadas en la cadena.
- **Seguridad criptográfica:** utiliza técnicas como funciones hash y firmas digitales.

## ¿Cómo se relacionan Blockchain y la criptografía?

Blockchain utiliza criptografía para diferentes funciones:

1. **Funciones hash:** ayudan a identificar los bloques y relacionarlos entre sí.
2. **Firmas digitales:** permiten verificar que una operación fue autorizada por quien posee la clave correspondiente.
3. **Claves criptográficas:** permiten controlar el acceso y la autorización de determinadas operaciones.

## Diagrama de arquitectura

```mermaid
flowchart LR
    A[Usuario] --> B[Transacción]
    B --> C[Nodo de la red]
    C --> D[Verificación]
    D --> E[Creación del bloque]
    E --> F[Bloque 1]
    F --> G[Bloque 2]
    G --> H[Bloque 3]
    H --> I[Cadena de bloques]
    I --> J[Red distribuida de nodos]
