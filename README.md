# Acceso a la API de Reddit
Por lo que pude investigar, dadas las medidas tomadas por la plataforma recientemente, sólo hay dos formas de acceder a la "Data API" de forma oficial, sin hacer web scraping:

1) A traves de Devvit, que sirve para el desarrollo de juegos, herramientas de moderación y widgets dentro de la plataforma, hosteado en los servidores de Reddit. No funciona para un microservicio o aplicación externa.
2) Mediante autenticación OAuth2, con client_id y client_secret. Para obtener estas credenciales hay que enviar una solicitud, que pasa por un proceso de aprobación manual. Envié la solicitud hace unos días y estoy a la espera de una respuesta.

También intenté completando el formulario oficial [reddit.com/prefs/apps](https://reddit.com/prefs/apps) que se utilizaba antes del cambio en las políticas de la plataforma, pero falla y te redirige a los dos métodos anteriores.
