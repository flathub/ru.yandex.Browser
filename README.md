# Yandex Browser

This is a Flathub source for Yandex Browser flatpak package.

To learn more about Yandex Browser, visit https://browser.yandex.ru/.

## Wayland support

Due to various crashes, confirmed as not related to Flatpak package (reproduced in AUR version of Yandex Browser),
Wayland support is disabled. You may enable it by yourself, using chrome-flags.conf and adding permission to Wayland
socket (via Flatseal, for example), but this configuration considered unsupported due to upstream bugs, and
Wayland-related issues will be closed without resolution until Yandex will introduce proper support for Wayland.

Last time Wayland support was checked was in July 2024. It will be periodically checked again until it will be proved
working flawlessly.

---

# Яндекс.Браузер

В этом репозитории содержатся исходные коды flatpak-пакета Яндекс.Браузера, который можно скачать из [Flathub](https://flathub.org/apps/details/ru.yandex.Browser).

Подробнее о Яндекс.Браузере можно узнать на официальном сайте https://browser.yandex.ru/.

## Поддержка Wayland

Из-за множества падений браузера, которые не зависят от Flatpak (подтверждено воспроизведением крэшей в версии браузера,
устанолвенной через AUR), поддержка Wayland отключена. Вы можете включить её через chrome-flags.conf и предоставление
прав на сокет Wayland (например, через Flatseal), но эта конфигурация является неподдерживаемой, и любые баги, связанные
с работой браузера в Wayland в такой конфигурации, будут закрываться без исправления до тех пор, пока Яндекс не внедрит
полноценную поддержку Wayland на своей стороне.

Последний раз проверка функциональности Wayland произведена в июле 2024 года. Поддержка Wayland не будет включена по
умолчанию, пока не будет достигнута стабильная работа бразуера в этом окружении.
