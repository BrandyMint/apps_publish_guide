Как опубликовать приложение
============

## Картинки и тексты

* название (30 символов для play)
* слоган (теглайн) (в play нет)
* описание (до 4 тыс)
* ключевые слова для AppStore (до 100 символов)
* Минмум 3 скриншона для AppStore (iPhone 3.5in Retina, iPhone 4in Retina, iPad Retina) и Google Play (смартфон, плашнет)
* __иконки приложения__
  - AppStore https://developer.apple.com/library/ios/documentation/userexperience/conceptual/mobilehig/IconMatrix.html
    - 29x29, 29x29@2x
    - 40x40, 40x40@2x
    - 50x50, 50x50@2x
    - 57x57, 57x57@2x
    - 60x60, 60x60@2x
    - 72x72, 72x72@2x
    - 76x76, 76x76@2x
    - 512x512, 512x512@2x (Artwork)
  - Google Play https://support.google.com/googleplay/android-developer/answer/1078870?hl=en
    - 36x36
    - 48x48
    - 72x72
    - 96x96
    - 512x512 (ArtWork)
    - 1024x512 (опционально, для раздела рекомендаций)
    - 180х120 (опционально, для рекламы)
* (опционально) сплэш-экраны
* (опционально) промо-видео на youtube (для play)
* (опционально) рекламный текст (до 80 play)



# iOS

* __Apple Developer account__
* создать сертификат разработчика в iOS Dev Center
* создать приложение в iOS Dev Center (App ID)
* создать provisioning profile (distribution) для App ID для публикации в AppStore
* создать приложение в iTunes Connect и заполнить необходимые поля https://itunesconnect.apple.com/WebObjects/iTunesConnect.woa
* подготовить iTunes Connect к загрузке бинарника (архива, binary) приложения
* Xcode
  * добавить иконки в приложение, (опционально) добавить сплэш-экраны
  * проверить target-версии и устройства, версию приложения (только цифры с точками)
  * поставить provisioning profile (distribution для AppStore), code signing identity
  * Scheme: iOS Device
  * Product > Archive
  * Organizer > выбрать приложение > выбрать архив > Distribute


# Ссылки

http://bjango.com/articles/appstoredescriptionpreviewer/
