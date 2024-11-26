# Entrega-experiencia-3
Entrega experiencia 3 Progamacion de aplicaciones moviles

INSTALAR:

npm install --save @capacitor-community/sqlite
▪ npm install @capacitor/preferences: este plugin nos permite almacenar datos en
nuestro dispositivo móvil o en el navegador.
▪ npm install @capacitor/device
▪ npm install sql.js: nos permite ejecutar sql en el navegador.

JSON
npm install -g json-server
json-server --watch almacen.json --host 0.0.0.0 --port 3000

Instalar las bibliotecas para android a través de capacitor:

- npm install @capacitor/android  ////// en caso de error por version: npm install @capacitor/core@latest
- npx cap add android

Configuramos la app con android:

- ionic capacitor sync android
- Ionic capacitor copy android
- Ionic capacitor open android

DPLOY

package-json: npm init –y
node_modules: npm install node
json-server versión 0.17.4: npm install json-server@0.17.4
cors: npm install cors

git status
git add .
git commit -m "TestApiDeploy“
git push -u origin main
