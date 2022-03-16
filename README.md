# risc-v-disassembler

В этом репозитории находится реализация дизассесмблера для файлов формата ```ELF32``` для архитектуры ```RISC-V```, а точнее секций ```.symtab``` и ```.text```.

В качестве входящих аргументов программе подаются путь до исходного файла формата ```ELF``` (по умолчанию ```input.elf```), путь до файла вывода (по умолчанию ```output.txt```).

Пример запуска программы из консоли:
```
make main
./main input.elf output.txt
```

Также в этом репозитории находится пример результата работы программы в файле ```output.txt```.
