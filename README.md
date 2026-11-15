🔍 HTB Sherlocks Writeups
Resoluciones de los Sherlocks de Hack The Box (investigaciones de DFIR y Blue Team), escritas por mí y con mis propias palabras, mientras me preparo para trabajar en SOC / análisis de amenazas.
No son copias ni traducciones de otros writeups: cada archivo cuenta cómo analicé la evidencia, qué busqué, dónde me trabé y qué aprendí en el proceso.
---
🎯 Objetivo del repositorio
Documentar mi aprendizaje en análisis forense y respuesta a incidentes.
Practicar el razonamiento de un analista: evidencia → hallazgo → conclusión.
Explicar cada paso para entenderlo de verdad, no solo responder las preguntas.
Armar un portfolio público de mi progreso en Blue Team.
---
📂 Estructura
Cada Sherlock es un archivo de texto (`.txt`) con el nombre del desafío:
```
htb-sherlocks-writeups/
├── README.md
├── Noxious.txt
├── PCAP Analyst.txt
└── Phishing Email Vip+.txt
└── ...
```
---
📝 Formato de cada writeup
Información general: nombre, categoría (DFIR, SOC, Threat Intel, etc.), dificultad.
Escenario: resumen de la situación planteada.
Artefactos disponibles: logs, capturas de red, imágenes de memoria, triage de disco, etc.
Análisis paso a paso: qué herramienta usé, qué busqué y qué encontré, pregunta por pregunta.
Línea de tiempo del ataque: qué hizo el atacante y cuándo.
IOCs y técnicas MITRE ATT&CK: indicadores y tácticas identificadas.
Lecciones aprendidas: cómo se habría detectado o prevenido.
---
📋 Índice de Sherlocks
Sherlock	Categoría	Dificultad	Artefactos / Herramientas
Nombre	DFIR	Easy	Ej: logs de eventos de Windows, Event Viewer
Nombre	SOC	Easy	Ej: captura de red, Wireshark
> Voy actualizando la tabla a medida que sumo writeups.
---
🛠️ Herramientas que uso
`Wireshark` · `Event Viewer`  · `Volatility` ·  `CyberChef` · `VirusTotal` · `Linux` · `Bash` · `ThunderBird`
(A medidad que avanzo agrego mas herramientas)
---
⚠️ Aviso importante
Solo publico writeups de Sherlocks retirados, respetando las reglas de Hack The Box.
Me enfoco en explicar el razonamiento y la metodología, no en listar respuestas sueltas.
Todo es con fines educativos.
---
👤 Sobre mí
Soy Jeremias Rositi, Profesionalizandome en Ciberseguridad. Buenos Aires, Argentina, con foco en Blue Team / SOC Analyst L1. Este repo es parte de mi camino para conseguir mi primera oportunidad en el rubro.
🔗 [Linkedin](linkedin.com/in/jeremias-rositi-079925271/)
🐙 GitHub: JeremiasRositi
🏴 [HTB Profile](https://app.hackthebox.com/users/856984?profile-top-tab=machines&ownership-period=1M&profile-bottom-tab=prolabs)
---
⭐ Si te sirvió algo de acá, dejá una estrella. ¡Y si encontrás un error o tenés una idea mejor, abrí un issue!
