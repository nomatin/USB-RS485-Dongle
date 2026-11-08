# Печатная плата USB–RS485

Двухслойная печатная плата преобразователя USB–RS485, разработанная в **Altium Designer**.

Основные компоненты:
- **CP2102N-A02-GQFN24** — USB–UART-мост.
- **ISOW1432DFMR** — изолированный приёмопередатчик RS-485 со встроенным преобразователем питания.

Предусмотрены защита интерфейсов, автоматическое управление направлением передачи, отключаемая терминация и индикация PWR/TX/RX.

При разработке использовалась собственная библиотека компонентов [ESKD Altium Libraries](https://github.com/nomatin/ESKD-altium-libraries). Конструкторская документация подготовлена с использованием [GOSTBOM-Fixes](https://github.com/nomatin/GOSTBOM-Fixes).

## Исходные файлы

- [Проект Altium](USB_to_RS485.PrjPcb)
- [Электрические схемы](SCH/)
- [Печатная плата](PCB/PCB.PcbDoc)
- [Чертежи Draftsman](Drawings/)
- [Настройки OutJob](OutJob/Schematics.OutJob)
- [3D-модель STEP и DXF](3D/)

## Производственные файлы

| Файлы | Назначение |
|---|---|
| [Gerber](OUTPUT/Manufacturing/Gerber/) | Изготовление платы |
| [NC Drill](OUTPUT/Manufacturing/NC%20Drill/) | Сверление отверстий |
| [BOM](OUTPUT/Manufacturing/BOM/) | Комплектация компонентов |
| [Pick & Place](OUTPUT/Manufacturing/Pick%20Place/) | Автоматизированный монтаж |
| [КД](OUTPUT/КД/) | Документация по ЕСКД |

[Принципиальная схема в PDF](OUTPUT/Schematics.PDF) · [Корпус](../Case/README.md)
