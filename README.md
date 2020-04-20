# Conky-Preset

#### English description:

My conky preset for Manjaro Linux.  
The author of the idea and the first version of Belyakov Igor aka OldHank.

#### Changes:
* Сompletely redesigned project
* Extended functionality
* Fixed values are changed to variables to work correctly on most systems without changing the code. (e.g. host name, distribution name, version, DE name)

#### Installation:
* Copy project files (conkyrc and folders) to the $HOME/.conky/ARCH-V-3/
* Enable using Conky Manager
* Enjoy

#### Note
* Appearance was edited for a screen resolution of 1920x1080, maybe you will have to make settings for your monitor.
* If it seems to you that the values are updated too often or if too many resources are consumed, increase the value of the `update_interval 0.7` variable
* If you have more or less than 4 processor cores, you need to duplicate the line `${font StyleBats:size=20}E${font}${voffset -6} CPU4: ${cpu cpu4}% ${alignr} ${cpubar cpu4 6,97} ${voffset 5}` increasing digits for example `${font StyleBats:size=20}E${font}${voffset -6} CPU4: ${cpu cpu4}% ${alignr} ${cpubar cpu4 6,97} ${voffset 5}` for 5 cores. Or comment out unnecessary lines, for example `#${font StyleBats:size=20}E${font}${voffset -6} CPU4: ${cpu cpu4}% ${alignr} ${cpubar cpu4 6,97} ${voffset 5}`
* Lines starting with `#` are comments
* Do not forget to change the name of the network interface
* If you want to change the distribution logo, edit the line `${image $HOME/.conky/ARCH-V-3/img/Manjaro.png -p 0,4 -s 40x40} ${voffset -5}` , changing the path to the image , for example `${image $HOME/.conky/ARCH-V-3/img/arch.png -p 0,4 -s 40x40} ${voffset -5}`. 256x256 images with transparent background are recommended.

#### TO DO:
- [X] Make English version
- [ ] Deal with fonts
- [ ] Fix minimizing widget when clicking the "Show Desktop" button
- [ ] Delete unnecessary fragments (Blanks)

Everything should work without problems, if you have errors let me know, i will try to fix it.  
All the best.

#### Русское описание:

Моя версия Conky пресета, адаптированная в первую очередь под Manjaro Linux.  
Автор идеи и первой версии Игорь Беляков aka OldHank.

#### Изменения:
* Проект полностью переработан
* Расширен функционал
* Фиксированные значения были изменены на переменные для корректной работы с большинством систем без редактирования кода. (имя хоста, название дистрибутива, версия дистрибутива, оконный менеджер)

#### Установка:
* Скопируйте файлы проекта (conkyrc и папки) в $HOME/.conky/ARCH-V-3/
* Включите используя Conky Manager
* Наслаждайтесь

#### Примечание:
* Оформление подгонялось под разрешение 1920x1080, возможно вам придётся отредактировать настройки под ваше разрешение.
* Если вам кажется, что значения изменяются слишком быстро или потребляется много ресурсов, увеличьте значение переменной `update_interval 0.7`
* Если у вас больше, чем 4 ядра процессора, вам нужно дублировать строку `${font StyleBats:size=20}E${font}${voffset -6} CPU4: ${cpu cpu4}% ${alignr} ${cpubar cpu4 6,97} ${voffset 5}` увеличивая номер ядра, например `${font StyleBats:size=20}E${font}${voffset -6} CPU4: ${cpu cpu4}% ${alignr} ${cpubar cpu4 6,97} ${voffset 5}` для 5 ядер. Или за комментировать ненужные строки, если у вас менее 4-х ядер, например `#${font StyleBats:size=20}E${font}${voffset -6} CPU4: ${cpu cpu4}% ${alignr} ${cpubar cpu4 6,97} ${voffset 5}`
* Строка начинающаяся с `#` является комментарием
* Не забудьте изменить название своего сетевого интерфейса
* Если вы хотите изменить логотип дистрибутива, отредактируйте строку `${image $HOME/.conky/ARCH-V-3/img/Manjaro.png -p 0,4 -s 40x40} ${voffset -5}` , изменив путь до нового изображения, например `${image $HOME/.conky/ARCH-V-3/img/arch.png -p 0,4 -s 40x40} ${voffset -5}`. Рекомендуются изображения с расширением 256x256 и прозрачным фоном.

#### Сделать:
- [X] Сделать Англоязычную версию
- [ ] Разобраться со шрифтами
- [ ] Постараться исправить сворачивание виджета при нажатии кнопки "Показать рабочий стол"
- [ ] Удалить ненужные фрагменты (не реализованные заготовки)

Всё должно работать "из коробки", но если у вас возникли проблемы дайте мне знать, постараюсь исправить.  
Всего наилучшего.

#### Work example / Пример работы:
![Image](https://github.com/XZVB12/Conky-Preset/raw/master/ScreenShot.png) ![Image](https://github.com/XZVB12/Conky-Preset/raw/master/ScreenShot-En.png)
