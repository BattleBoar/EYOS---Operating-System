
**Делай как хочешь, делай что хочешь.**

# EYOS - Everything on your computer belongs to you #
> EYOS not DOS like, EYOS is Linux-BSD like.
## О нём

Проект создаётся энтузиастом.
Пытаемся создать ОС которую можно использовать для своих нужд и модифицировать для определённых задач
Код распростроняется свободно и можно свободно модифицировать kernel, syscalls, drivers и т.п.

## Технологии и сборка

*   **Языки:** C, N/F-ASM (Планируется C++, Rust)
*   **Целевая архитектура:** x86_64
*   **Разрядность:** 64bit
*   **Структура ядра:** Monolitic, MultiTask, 

### Требования для сборки
#### Arch-Chachy-Atrix-Endeavour-Manjaro
```bash
sudo pacman -S base-devel nasm gcc git cmake xorriso
```

#### Debian-Kali-Mint-Ubuntu-Rassbery
```bash
sudo apt install base-devel nasm gcc git cmake xorriso
```

### Клонирование

```bash
   git clone https://github.com/BattleBoar/EYOS---Operating-System.git
   cd EYOS---Operating-System/
```
### Компилирование (Тестируется)
``` bash
    ./build86.sh 
    cd build86
```
### Запуск _Qemu_ (Тестируется)

```bash
   qemu-system-x86_64 -cdrom eyos.iso -m 1g
```
#### или для .img

```bash
   qemu-system-x86_64 -cdrom eyos.img -m 1g
```

## Лицензия

Это свободное программное обеспечение. Вы можете использовать, изучать, изменять и распространять его в соответствии с условиями лицензии GNU General Public License v3.0. Полный текст доступен в файле LICENSE.

> Примечание: Это хоть и проект с вободным распростронением, но: выдавать эту ос за полностью свою, без прямой ссылки на офф проект приравневается к вороству.
