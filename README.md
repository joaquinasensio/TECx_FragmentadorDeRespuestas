# TECx_FragmentadorDeRespuestas
A los fines de garantizar el anonimato de cada empresa en el monitor estadístico TECx, incluso el de "empresar singulares", la aplicación desarrollada en python, fragmenta las respuestas en n formularios electrónicos que simulan respuestas de n empresas distintas.

Los formularios electrónicos, en la plataforma LimeSurvey, generan una base de datos en la nube que solo tiene acceso EconomicTrends, sin posibilidad de identificar a ninguna empresa respondente.

El repositorio esta formado por un archivo 'main.py', encargado de vincular y armar el aplicativo; un archivo 'bases.py' que detalla el envío de respuestas de cada perfil a la plataforma LimeSurvey; y por último un archivo 'KvEstructura.kv' que define la estructura del aplicativo.

### Líbrerias fundamentales para poder correr la aplicación:
- pandas
- selenium
- kivy
- os
- random
