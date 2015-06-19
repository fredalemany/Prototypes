# Art Mobilis - Prototypes applications

Projet Art Mobilis de parcours culturel au sein de territoires.

Développé collaborativement par plusieurs développeurs, graphistes et artistes.

Dossier application openFrameworks (C++).

Nécessite les ofxAddons (à mettre dans le dossier addons de openFrameworks):
 - ofxAruco: https://github.com/brucelane/ofxAruco ( modifié pour éviter run-time error décrite ici: https://github.com/arturoc/ofxAruco/issues/3 )
 - ofxCv: https://github.com/kylemcdonald/ofxCv
 - ofxLibwebsockets https://github.com/labatrockwell/ofxLibwebsockets
 - ofxTimeline https://github.com/YCAMInterlab/ofxTimeline
 - ofxTween https://github.com/arturoc/ofxTween.git
 - ofxMSATimer https://github.com/obviousjim/ofxMSATimer
 - ofxTimecode https://github.com/YCAMInterlab/ofxTimecode
 - ofxTextInputField https://github.com/Flightphase/ofxTextInputField (j'ai commenté les lignes 341 et 346-351 du .cpp TODO: #define)
 - ofxMaps https://github.com/bakercp/ofxMaps (ajouter #define M_E 2.71828182845904523536 #define M_PI 3.14159265358979323846 // devant key_to_value_type _key_to_value; )

Imprimer les marqueurs du dossier bin/data: board.png et/ou boardImage.png

Sous Linux:
![Capture](assets/linux.png)

Sous Windows:
![Capture](assets/windows.jpg)