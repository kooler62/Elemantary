# Elementary





Добавить языки системы 

перевести язык, желательно не переводить системные папки 

След. команда позволяет менять раскладку по Ctrl+Shift 
gsettings set org.pantheon.desktop.gala.keybindings switch-input-source "['<Ctrl>Shift_L', '<Ctrl>>Shift_R', '<Shift>Control_L', '<Shift>Control_R']" 

sudo apt-get install aptitude
sudo aptitude install firefox-locale-ru
install firefox with app-srore
# Внешний вид
## Elementary tweak
sudo add-apt-repository ppa:mpstark/elementary-tweaks-daily
sudo apt-get update
sudo apt-get install elementary-tweaks

и выйти из сисетмы tweak 
теперь можно установить темы для 
Вот, как установить Numix-Circle Icon в OS: 
sudo apt-add-repository ppa:numix/ppa 
sudo apt-get update 
sudo apt-get install numix-icon-theme-circle 
# Програмы для востановления системы
Установка Systemback 
позволяет востанавливать систему и создавать точки а также создавать live образы системы 
compizomania.blogspot.com/2014/07/systemback-linux.html?showComment=1404884898999#c4556768932382032390 

sudo add-apt-repository ppa:nemh/systemback 
sudo apt-get update 
sudo apt-get install systemback 

Если вы решили удалить Systemback из системы, выполните этикоманды в терминале: 

sudo add-apt-repository -r ppa:nemh/systemback 
sudo apt-get update 
sudo apt-get purge systemback 

