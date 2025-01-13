# de2025_sk

b=main sh=PVE-DE-BASH.sh opts=(-c 'https://disk.yandex.ru/d/HDgvq-iMbduqag' -z) ;curl -sfOL "https://raw.githubusercontent.com/10maksim01/de2025_sk/$b/$sh"&&{ chmod +x $sh&&./$sh "${opts[@]}";rm -f $sh;true;}||echo -e "\e[1;33m\nОшибка скачивания: проверьте подключение к Интернету, настройки DNS, прокси и URL адрес\ncurl exit code: $?\n\e[m">&2
