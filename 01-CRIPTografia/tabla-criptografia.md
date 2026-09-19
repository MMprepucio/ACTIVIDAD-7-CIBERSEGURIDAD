# Tabla de tipos de criptografía

| Tipo de criptografía | ¿Cómo funciona? | Ventajas | Desventajas | Ejemplos actuales |
|---|---|---|---|---|
| Criptografía simétrica | Utiliza la misma clave para cifrar y descifrar la información. | Es rápida y eficiente para proteger grandes cantidades de datos. | La clave debe compartirse de forma segura entre las personas o sistemas. | AES, ChaCha20 |
| Criptografía asimétrica | Utiliza una clave pública y una clave privada. | Permite intercambiar información sin compartir previamente una clave secreta. | Es más lenta que la criptografía simétrica y requiere más recursos. | RSA, ECC |
| Funciones hash | Transforman los datos en un valor de longitud fija. | Permiten verificar la integridad de la información y son útiles para almacenar contraseñas de forma segura. | No están diseñadas para recuperar el mensaje original. | SHA-256, SHA-3 |
| Criptografía cuántica | Utiliza principios de la física cuántica para proteger determinadas comunicaciones. | Puede detectar ciertos intentos de interceptación de la comunicación. | Requiere infraestructura especializada y actualmente tiene aplicaciones limitadas. | Distribución cuántica de claves (QKD) |
| Criptografía poscuántica | Utiliza algoritmos diseñados para resistir ataques realizados mediante computadores cuánticos. | Puede implementarse en sistemas informáticos convencionales y busca proteger información frente a futuras amenazas cuánticas. | Algunos algoritmos pueden requerir más recursos o producir claves y firmas de mayor tamaño. | ML-KEM, ML-DSA, SLH-DSA |
