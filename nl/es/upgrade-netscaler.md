---
copyright:
  years: 1994, 2018

lastupdated: "2018-06-28"
---

{:shortdesc: .shortdesc}
{:new_window: target="_blank"}

# Actualización de Citrix NetScaler VPX

**NOTA:** Debe estar conectado a la VPN antes de intentar este procedimiento.

1. Inicie sesión en la IP de gestión de NetScaler.
2. Pulse **Actualización del sistema**.
4. Seleccione **Local** desde la lista desplegable **Elegir archivo**. 
4. Descargue el archivo de actualización correcto desde la siguiente ubicación:

	[Versiones disponibles de NetScaler ![Icono de enlace externo](../../icons/launch-glyph.svg "Icono de enlace externo")](http://downloads.softlayer.local/citrix/netscaler/){: new_window}
	
	**NOTA:** Debe estar conectado a la VPN de IBM Cloud Infrastructure para acceder a este enlace.

5. En la pantalla Actualizar software, vaya a la ubicación del archivo de actualización y pulse **Actualizar**. El firmware se actualizará.
6. En la ventana Actualización del sistema resultante, se le solicitará que rearranque. Pulse **Cerrar**.
7. Vuelva a **Sistema**, y pulse **Rearrancar**.
8. Después de la actualización, cierre todas las instancias de navegador y borre la memoria caché del sistema antes de acceder al dispositivo.

**NOTA:** La interfaz de usuario puede diferir dependiendo de la versión actual del NetScaler VPX.



