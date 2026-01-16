---
marp: true
theme: dark
paginate: true
footer: De los circuitos a las abstracciones
---

# De los circuitos a las abstracciones
## Cómo hemos llegado hasta aquí

---

# Qué es esta charla
- No es una clase de protocolos
- No es una comparativa de tecnologías
- Es una historia técnica vivida

> Entender el modelo > memorizar siglas

---

# Por qué esta historia
- He trabajado en:
  - Mundo táctico
  - Mundo estratégico
- He visto:
  - El inicio
  - La transición
  - El estado actual

> No lo he estudiado, lo he vivido

---

# Punto de partida
## Donde estáis vosotros

- Gabinete RBA
- Equipos antiguos
- Circuitos digitales

> Esto no es obsoleto. Es el origen.

---

# Eurocom
## Qué era realmente

- No era un protocolo
- No era un medio
- Era un contrato de servicio

> Servicio garantizado, medio indiferente

---

# Ya trabajáis con abstracciones
- Usáis Eurocom
- Sin saber qué hay debajo
- Sin preocuparos del transporte

> Eso es una capa de abstracción

---

# Dos mundos en paralelo

- Mundo táctico
- Mundo estratégico

> Diferente escala, mismo principio

---

# Mundo táctico (antes)

- Voz PCM 64 kb
- Radio LOS
- Satélite
- Cifrado del enlace

> Se protegía el enlace, no el servicio

---

# Mundo estratégico (antes)

- Jerarquía digital plesiócrona
- E1 como unidad básica
- Centrales telefónicas
- Radio / SDH / ATM

> El E1 fue el Eurocom estratégico

---

# El modelo común

- Troncales abstractos
- Servicios en los extremos
- Transporte indiferente

> Diseñábamos servicios, no redes

---

# Aparece el problema

- La voz ya no es suficiente
- Empiezan los datos
- Primeros intentos

> Los datos entran como invitados

---

# Primeros datos

- ETDA
- 64 kb
- Router por serie

> Funciona, pero no escala

---

# FlexiMUX
## El puente entre mundos

- Agregación de canales
- 128 kb / 256 kb
- Táctico ↔ Estratégico

> No rompimos nada, lo estiramos

---

# DTU + router
## Nace el nodo

- Circuito punto a punto
- Router conectado
- CIS iniciales

> Pasamos de enlaces a nodos

---

# La pregunta clave

## ¿Para qué tanto hardware?

- DTU
- Multiplexores
- Adaptadores

> El router ya habla E1

---

# Nace la WANC2 / IPC2

- E1 dedicados a datos
- Router central
- IP nativa

> El E1 deja de ser voz por defecto

---

# Tres grandes consumidores de E1

- Centrales telefónicas
- Routers de mando y control
- Red FlexiMUX

> Equilibrio temporal

---

# FlexiMUX evoluciona

- De punto a punto
- A red multipunto
- Todos con todos

> Abstracción total de la topología

---

# Todo sobre IP

- Red común
- Servicios encima
- Transporte genérico

> La red deja de ser especial

---

# Cambio de seguridad

## Antes
- Cifrar enlaces
- Seguridad por infraestructura

## Ahora
- Cifrar servicios
- Seguridad por capas

---

# Nueva idea de seguridad

> Dejamos de proteger la carretera  
> y empezamos a proteger los vehículos

---

# Satélite cambia de rol

- De E1 a Ethernet
- Router integrado
- Nodo de red

> El terminal ya no es un tubo

---

# Táctico moderno

- Router "negro"
- Cifradores por servicio
- Voz IP
- Datos IP

> Plug & Play operativo

---

# Radioenlaces tácticos

- No previstos en el diseño
- Integraciones artesanales
- Más routers, más cifrado

> Lo que no escala, muere

---

# El choque de realidad

## WAN PG vs WAN C2

- WAN PG → 100 Mbps
- WAN C2 → 2 Mbps
- Demanda de datos creciente

> La VTC lo deja claro

---

# No hay dinero

- MC3 muere a medias
- No hay red nueva
- Decisiones pragmáticas

> Ingeniería real, no ideal

---

# Solución intermedia

- Modernizar solo satélite
- PD25L
- IP en el acceso

> Se mantiene el esqueleto

---

# La decisión lógica

- Una sola red
- MPLS
- QoS
- Reservas para mando y control

> Si ya existe, úsala

---

# Nuevo modelo de seguridad

- Red considerada insegura
- Seguridad en los extremos
- Segmentación
- Control

---

# STIC y acreditaciones

- Firewalls en ambos extremos
- Marcas distintas
- IDS / IPS

> Seguridad por diseño

---

# I3D
## Donde estamos hoy

- Infraestructura compartida
- IP
- Servicios segmentados
- Acreditaciones

> El medio ya no importa

---

# Las capas
## Por fin explícitas

- OSI como mapa mental
- TCP/IP como implementación

> OSI no es un estándar, es una forma de pensar

---

# La idea clave

- Enlaces
- Servicios
- Abstracciones

> Todo es lo mismo a distinto nivel

---

# Qué quiero que os llevéis

- No memoricéis tecnologías
- Entended modelos
- Pensad por capas

> Eso os valdrá siempre

---

# Pregunta final

## ¿Creéis que lo que estudiáis hoy
## os servirá dentro de 10 años?

---

# Respuesta

> Sí, si entendéis las capas  
> No, si solo memorizáis siglas

---

# Gracias
## Preguntas
