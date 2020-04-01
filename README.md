ИГРА "ДОРОГА ДОМОЙ"

Попытка создать программу с игрой из детства с целью изучения языка GAMBAS

_Правила игры:_

В игре может участвовать 1-4 игроков.
У каждого игрока есть 4 игровые фишки, которые в начале игры находятся в запасе (индикатор справа от игрового поля).
Игроки по очереди бросают игральный кубик. Если выпала "6" игрок может выставить одну свою фишку на поле.
Также выпавшая "6" дает право на повторный бросок.
Фишки выставляются для 1го игрока - в левом нижнем углу
                   для 2го игрока - в левом верхнем углу
                   для 3го игрока - в правом верхнем углу
                   для 4го игрока - в правом нижнем углу.
Если у игрока на поле есть фишки, то после броска он может подвинуть одну из них на количество шагов, выпавших на кубике.
Бордюры (шахматные слоны) и чужие фишки мешают проходу. Их можно "съесть" только точно попав на занятое ими поле.
Фишки игроков движутся по внешнему кругу поля по часовой стрелке. Цель - пройти каждой фишкой полный круг и "припарковать" ее
в своем углу (как были выстроены бордюры вначале).

_Установка_

В папке Releases есть установочные файлы для разных платформ.
Для запуска без установки используйте файл из папки Releases/standalone
Распакуйте его и запустите RoadToHome.gambas
Потребуется установить следующие зависимости:

gambas3-runtime
gambas3-gb-image
gambas3-gb-form
gambas3-gb-media
gambas3-gb-media-form
gambas3-gb-sdl2-audio
gambas3-gb-gui
gambas3-gb-qt5




To Do (это для меня чтобы не забыть :) ):
   
   - компьютерные противники
   - может анимацию движения фигур
   - звуки движения, "съедания" фигур, победы
  
   
Исправить:
   
   - Определение бордюра сделать не по количеству оставшихся, а через коллизии
