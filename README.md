# criando_app_android
npm install http-server -g ( interpretador de javaScript para desktopp) (npm - node packge manager) /-g/ instalar de forma global na máquina

*PWA - standalone
*PWA workbox-cli --global
*PWA vue-cli (Não precisa do manifest se usar)

PWA - precisa ter: HTML +css
      manifest.json (site gerador de manifest)
      service_worker.js (vai ser criado -npm install workbox-cli 
                                         workbox wizard
                                         workbox generate SW __________ config file
      
Index.html ( com : <link rel="manifest" href= "manifest.json"> -> este json foi criado no:  /https://app-manifest.firebaseapp.com/


{
  "theme_color": "#2196f3",
  "background_color": "#2196f3",
  "display": "browser",
  "scope": "/",        _________> todo o site
  "start_url": "/"      ________> "/index.html"
}

