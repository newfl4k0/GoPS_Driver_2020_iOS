# Nat-GoPPlusDriver-iOS

Native iOS GoPPlus Driver App

- iOS 9.3+ 
- Push
- Cambios Dic 2019 - Sept 2020 (Google Directions + iOS14)
- iOS 14.0
- Path Tarjeta de Crédito - Banorte
- Oct 2020 v.76

# Guía de Instalación

1. Descargar el repositorio.
2. Instalar CocoaPods (si aplica) : https://guides.cocoapods.org/using/getting-started.html
3. Si los Frameworks o Productos del Proyecto Pods están en rojo, instalar los pods con el podfile incluído en el proyecto. 
3a. Al instalar los pods, ir al proyecto XCode y eliminar la carpeta Pods>>Pods>>AFNetworking>>UIKit, eliminar la referencia.
3b. Si aun existen elementos en rojo, instalar Google manualmente: https://developers.google.com/maps/documentation/ios-sdk/start#install-manually
4. Verificar Scheme: fa , Target: Any iOS Device
5. Cambiar la versión según aplique.
6. Compilar
