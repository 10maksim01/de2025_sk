# de2025_sk

```
sh='PVE-DE-BASH.sh';curl -sOL "https://raw.githubusercontent.com/10maksim01/de2025_sk/main/$sh"&&chmod +x $sh&&./$sh -c https://disk.yandex.ru/d/EQoUMl5FSfPjyg -z;rm -f $sh
```
```
(b=testing_api opts=( PVE-DE-BASH.sh -c 'https://disk.yandex.ru/d/EQoUMl5FSfPjyg' -z ) ;curl -sfOL "https://raw.githubusercontent.com/10maksim01/de2025_sk/$b/${opts[0]}"&&{ chmod +x ${opts[0]}&&./"${opts[@]}";rm -f ${opts[0]};:;}||echo -e "\e[1;33m\nОшибка скачивания: проверьте подключение к Интернету, настройки DNS, прокси и URL адрес\ncurl exit code: $?\n\e[m">&2)
```
