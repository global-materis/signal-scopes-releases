<div align="center">
<img width="128" height="128" alt="128x128" src="https://github.com/user-attachments/assets/6f9c8c71-0dee-4165-887f-7a097e23534d" />

# SignalScope

**Mira la señal de toda tu red WISP de un vistazo.**

Monitor de escritorio para operadores con radios **Ubiquiti airMAX**. Escanea tu
red, abre sesión en cada radio (SSH/HTTP) y te muestra la **señal en dBm en
tiempo real**, con un semáforo que te dice al instante qué enlaces están sanos y
cuáles piden atención. Es de **solo lectura**: nunca cambia la configuración de
tus radios.
</div>

<img width="1920" height="1032" alt="SignalScope-Monitor" src="https://github.com/user-attachments/assets/9f432c4e-9cc5-4595-a150-fcda2cdec915" />

## En acción

<table>
<tr>
<td width="50%" valign="top">

<img width="1920" height="1032" alt="SignalScope-Station-Diagnostic" src="https://github.com/user-attachments/assets/2f272fb8-d680-4033-a6dd-64268397dbdb" />

**Diagnóstico automático, no solo un color.** Cada estación explica su estado:
señal contra la esperada a su distancia, ruido/SNR, calidad de enlace y
throughput real vs. esperado.

</td>
<td width="50%" valign="top">

<img width="1920" height="1032" alt="SignalScope-Visor-AP" src="https://github.com/user-attachments/assets/c0506873-c6cc-4831-bcee-8be2e49aa574" />

**Tus Puntos de Acceso, controlados.** Estado *Operativo / Carga alta /
Saturado*, frecuencia, canal, clientes conectados, TX power, CCQ y uptime de
cada antena base.

</td>
</tr>
<tr>
<td width="50%" valign="top">

<img width="1920" height="1032" alt="SignalScope-Welcome" src="https://github.com/user-attachments/assets/a3021b99-3d6a-4f0c-bc8d-5da8bd30dc59" />


**Empieza en segundos.** Abre un proyecto guardado para retomar tus enlaces y
referencias, o escanea una red desde cero. Los proyectos `.sscope` guardan la
red completa, cifrada localmente.

</td>
<td width="50%" valign="top">

<img width="1920" height="1032" alt="SignalScope-Visor" src="https://github.com/user-attachments/assets/e290f478-a019-4cd8-a5b8-5b457e8853b0" />

**Comparte sin filtrar datos.** Un snapshot de solo lectura con los datos
privados protegidos (nombres e IPs recortados) que cualquier otro SignalScope
abre en modo visor.

</td>
</tr>
</table>

## Por qué SignalScope

- 🛰️ **Toda tu red en una tabla, en vivo.** Descubre los radios por ARP y abre
  sesión SSH/HTTP en cada uno; la señal en dBm (local y remota) se refresca sola.
- 🚦 **Un semáforo que entiende de enlaces.** Verde / amarillo / rojo por
  umbrales dBm — o relativo a una **referencia que fijas por antena**. Sabes de
  inmediato qué enlace se degradó frente a cómo estaba.
- 🧠 **Diagnóstico que explica el porqué.** No solo marca "crítico": *"señal 12
  dB por debajo de lo esperado a 1.2 km, ruido alto, downlink degradado"*. Te
  dice **dónde mirar**, no solo que algo anda mal.
- 📸 **Historial y comparación.** Snapshots con Δ contra el estado actual,
  referencias por antena y **reportes en PDF/Excel** para el cliente o tu registro.
- 🔒 **Solo lectura, de verdad.** Nunca envía comandos de configuración: cero
  riesgo de tumbar un enlace por accidente.
- 🤝 **Comparte sin exponer.** Un snapshot `.ssnap` recorta nombres e IPs
  sensibles y el otro operador lo abre en modo visor.

## Release

- Descarga la última versión desde
  [Releases](https://github.com/global-materis/signal-scopes-releases/releases/latest)
  (`SignalScope_x.y.z_x64-setup.exe`).
- La aplicación instalada avisa sola cuando hay una versión nueva.
- Licencias y soporte: support@materis.io

## Feedback

💬 Tu opinión nos ayuda a mejorar — escríbeme a [support@materis.io](mailto:support@materis.io).
