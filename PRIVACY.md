# Política de privacidad de Polaris GPS

*Última actualización: 5 de noviembre de 2026* · [English below](#privacy-policy-of-polaris-gps)

Polaris GPS es una aplicación de escritorio de Mendikat. **No envía datos personales a Mendikat salvo que conectes tu
cuenta de Mendikat o le envíes un track**, y solo lo necesario para eso. No hay publicidad, telemetría, analítica ni
informes de errores automáticos.

## Datos en tu equipo

- Los tracks, rutas y waypoints que abres o guardas se quedan en tu equipo, en los archivos que tú eliges.
- Los ajustes (`%APPDATA%\Polaris GPS\settings.json`), el índice de las carpetas de mapas y tracks y el registro de
  la aplicación (`%LOCALAPPDATA%\Polaris GPS`) también se guardan solo en tu equipo. El registro no incluye el nombre
  de tu carpeta de usuario, tu contraseña ni tu permiso de acceso. Puedes borrarlos cuando quieras.

## Cuenta de Mendikat y envío de tracks

Conectar una cuenta de Mendikat es opcional y solo hace falta para _Comunicaciones › Enviar a Mendikat_.

- **Al conectar con usuario y contraseña**, la aplicación los envía a mendikat.net por una conexión cifrada (HTTPS)
  para obtener un permiso de acceso. La contraseña no se guarda.
- **Al conectar con Google**, inicias sesión en Google en tu navegador. Google entrega a la aplicación un permiso para
  leer tu nombre y tu dirección de correo, que se envía a mendikat.net para identificar tu cuenta (o crearla si no
  existe). Ni la aplicación ni Mendikat reciben tu contraseña de Google.
- **En tu equipo** se guardan el permiso de acceso de Mendikat y tu usuario, nombre y correo, en el Administrador de
  credenciales de Windows, cifrados por Windows para tu usuario. **Desconectar** los borra.
- **Al enviar un track**, la aplicación envía a mendikat.net la posición de algunos puntos del track, para buscar las
  cumbres próximas, y después el archivo GPX con la descripción que elijas, que se publica en las cumbres que marques
  con tu nombre de usuario. Desde ese momento Mendikat trata el track como cualquier otro que publiques en la web,
  según la política de privacidad de [www.mendikat.net](https://www.mendikat.net); puedes borrarlo desde la web.

## Conexiones a servicios de terceros

Para algunas funciones la aplicación se conecta a servicios públicos de terceros. Estos servicios reciben tu dirección
IP, la versión de la aplicación (en el encabezado *User-Agent*) y lo que hace falta para responder:

| Función | Servicio | Qué se envía |
|---|---|---|
| Mapas de fondo | IGN de España, OpenStreetMap, OpenTopoMap, CyclOSM, Esri, IGN de Francia (Géoportail), MTBmap | Las teselas de la zona que ves en el mapa |
| Altitudes (modelo digital del terreno) | IGN de España (servicios.idee.es) | La zona de los puntos cuya altitud se calcula |
| Cálculo de rutas | BRouter (brouter.de) | Los puntos de la ruta que dibujas |
| Buscar un lugar | Nominatim de OpenStreetMap | El texto que buscas y la zona visible del mapa |
| Conectar con Google (solo si lo eliges) | Google | El inicio de sesión que haces en el navegador |
| Buscar actualizaciones (solo cuando la eliges en el menú) | GitHub | Ninguno: solo se consulta la última versión publicada |
| Cartografía en línea ECWP | El servidor cuya dirección escribes | La zona que ves en el mapa |

Mendikat no recibe ni guarda estos datos. Cada servicio los trata según su propia política de privacidad. Si no usas
estas funciones, la aplicación no se conecta a ellos; los archivos locales y los mapas locales funcionan sin conexión.

## Menores

La aplicación no está dirigida específicamente a menores. Solo envía datos personales a Mendikat cuando quien la usa
conecta su cuenta de Mendikat o le envía un track.

## Cambios y contacto

Si esta política cambia, se publicará aquí con su nueva fecha. Para cualquier duda: [www.mendikat.net](https://www.mendikat.net).

---

# Privacy policy of Polaris GPS

*Last updated: 5 November 2026*

Polaris GPS is a desktop application by Mendikat. **It does not send any personal data to Mendikat unless you connect
your Mendikat account or send it a track**, and then only what that needs. There is no advertising, telemetry,
analytics or automatic error reports.

## Data on your computer

- The tracks, routes and waypoints you open or save stay on your computer, in the files you choose.
- The settings (`%APPDATA%\Polaris GPS\settings.json`), the index of the map and track folders and the application log
  (`%LOCALAPPDATA%\Polaris GPS`) are also stored only on your computer. The log does not include the name of your user
  folder, your password or your access permission. You can delete them at any time.

## Mendikat account and sending tracks

Connecting a Mendikat account is optional and only needed for _Communications › Send to Mendikat_.

- **When you connect with your user name and password**, the application sends them to mendikat.net over an encrypted
  connection (HTTPS) to obtain an access permission. The password is not stored.
- **When you connect with Google**, you sign in to Google in your browser. Google gives the application a permission
  to read your name and e-mail address, which is sent to mendikat.net to identify your account (or create it if it
  does not exist). Neither the application nor Mendikat receives your Google password.
- **On your computer**, the Mendikat access permission and your user name, name and e-mail are stored in the Windows
  Credential Manager, encrypted by Windows for your user. **Disconnect** deletes them.
- **When you send a track**, the application sends mendikat.net the position of some points of the track, to find the
  nearby summits, and then the GPX file with the description you choose, which is published on the summits you check
  under your user name. From then on Mendikat handles the track like any other you publish on the website, under the
  privacy policy of [www.mendikat.net](https://www.mendikat.net); you can delete it from the website.

## Connections to third-party services

Some features connect to public third-party services. These services receive your IP address, the application version
(in the *User-Agent* header) and what they need to answer:

| Feature | Service | What is sent |
|---|---|---|
| Background maps | IGN Spain, OpenStreetMap, OpenTopoMap, CyclOSM, Esri, IGN France (Géoportail), MTBmap | The tiles of the area shown on the map |
| Elevations (digital terrain model) | IGN Spain (servicios.idee.es) | The area of the points whose elevation is computed |
| Route calculation | BRouter (brouter.de) | The points of the route you draw |
| Place search | OpenStreetMap Nominatim | The text you search for and the area shown on the map |
| Connect with Google (only if you choose it) | Google | The sign-in you make in the browser |
| Check for updates (only when chosen in the menu) | GitHub | Nothing: only the latest published version is read |
| ECWP online maps | The server whose address you type | The area shown on the map |

Mendikat does not receive or store this data. Each service handles it under its own privacy policy. If you do not use
these features, the application does not connect to them; local files and local maps work offline.

## Children

The application is not specifically aimed at children. It only sends personal data to Mendikat when the person using
it connects their Mendikat account or sends it a track.

## Changes and contact

If this policy changes, it will be published here with its new date. For any question:
[www.mendikat.net](https://www.mendikat.net).
