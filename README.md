# 🛡️ Informe Técnico de Incidente de Seguridad  

Este repositorio contiene la documentación y la máquina virtual utilizada para recrear y analizar un incidente de seguridad en un servidor Linux.  

## 📂 Contenido del repositorio  

- **Informe técnico**: análisis forense del ataque, descripción de eventos y medidas de mitigación.  
- **Cronología de la intrusión**: tabla detallada con fechas, acciones del atacante y evidencias encontradas.  
- **Archivos generados en la máquina comprometida**: scripts maliciosos, registros modificados y cron jobs.  
- **Máquina virtualizada**: imagen del sistema afectado con todos los cambios aplicados durante la simulación del ataque.  

## 🎯 Objetivo  

El propósito de este proyecto es mostrar de forma práctica cómo un atacante puede:  

- Crear usuarios no autorizados.  
- Ejecutar y programar scripts maliciosos.  
- Intentar exfiltración de datos sensibles.  
- Manipular historiales y registros para ocultar actividad.  

A la vez, se documenta el proceso de detección, análisis y respuesta para comprender mejor la trazabilidad de un incidente.  

## ⚙️ Uso de la máquina virtual  

1. Importa la máquina virtual en tu software de virtualización (VirtualBox, VMware, etc.).  
2. Inicia el sistema y revisa los directorios indicados en el informe.  
3. Analiza los archivos creados por el atacante:  
   - `/usr/local/bin/backup2.sh`  
   - `/etc/cron.d/sys-maintenance`  
   - `.bash_history` de usuarios comprometidos 
4. Analiza la caperta creada por el analista /home/IR/ 
4. Contrasta con el informe para comprender la secuencia de compromiso.  

✍️ Autor: Roger. 
📅 Fecha: Agosto 2025  
