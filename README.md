# ntpwd
Based on Offline Windows Password &amp; Registry Editor by Petter N Hagen https://pogostick.net/~pnh/ntpasswd/

В связи с тем, что оригинальный проект не работает на компьютерах с 4 и более гигабайтами оперативной памяти, был создан этот форк. К счастью, основная утилита chntpw присутствует в составе SystemRescueCd (http://www.system-rescue-cd.org/Download/). Но она довольно неудобна при работе напрямую, поэтому были взяты оригинальные скрипты и из них были убраны все ненужные теперь процедуры предварительной инициализации.

Способ использования:
1. Скопировать файлы на флешку с установленным SystemRescueCd
2. Загрузиться в SystemRescueCd
3. При необходимости сделать файлы исполняемыми (chmod +x *.sh)
4. Запустить main.sh и следовать инструкциям на экране

This fork has been created because the original project does not work on computers with 4 and above gigabytes of RAM. The main utility chntpw is already inside SystemRescueCd (http://www.system-rescue-cd.org/Download/). Therefore all unnecessary initialization procedures were removed from original scripts.

How to use:
1. Copy files on a flash drive with SystemRescueCd installed
2. Boot in SystemRescueCd
3. Make the files executable (chmod +x *.sh) if necessary
4. Run main.sh and follow the instructions on the screen
