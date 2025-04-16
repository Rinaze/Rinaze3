## Диаграмма классов для задания Практика «Простые команды Brainfuck»
![image](https://github.com/user-attachments/assets/69c1a019-8896-4fc9-a90e-6905c3350eee)

### Описание основных сущностей
- BrainfuckBasicCommands:
  - Этот класс содержит статические методы для регистрации команд для виртуальной машины Brainfuck.
  - Основным методом является , который берет экземпляр и настраивает его с помощью основных команд Brainfuck.RegisterToIVirtualMachine
- IVirtualMachine:
  - Этот интерфейс представляет собой виртуальную машину Brainfuck.
  - Он имеет свойства для доступа к памяти (в виде массива байтов) и указателя памяти (в виде целого числа).MemoryMemoryPointer
  - Метод используется для связывания символа с действием, которое должно быть выполнено на виртуальной машине.RegisterCommand
