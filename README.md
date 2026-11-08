# Крестики-нолики (Tic-Tac-Toe)

Простая игра «Крестики-нолики» на Windows Forms (C#).

## Правила

Правила игры: на поле 9 клеток (3×3).  
Два игрока по очереди ставя - **X** и **O**.  

Когда игра заканчивается, все кнопки блокируются.  
Кнопка **"Начать заново"** сбрасывает поле и начинает новую партию.

# Игра в процессе
<img width="544" height="657" alt="Image" src="https://github.com/user-attachments/assets/cd58f5d5-341d-4b1e-95d4-b0634388ea06" />

# Ничья

<img width="539" height="660" alt="Image" src="https://github.com/user-attachments/assets/486d6e05-dc04-4080-b143-9141df604c5f" />

# Начало игры

<img width="540" height="652" alt="Image" src="https://github.com/user-attachments/assets/5663cf32-c510-4983-be14-92d43c1943df" />

## Что нужно, чтобы запустить

- Visual Studio
- Windows Forms

## Как я делал

### 1. Создал проект

Создал проект **Приложение Windows Forms (.NET Framework)** на C#`.

В свойствах формы поставил:
- `Text = Form1`
- Размер удобный для 3×3 сетки

### 2. Добавил кнопки и метки

На форму положил:
- 9 кнопок (`button1` … `button9`) — это клетки поля
- `label2` — для сообщения о победе или ничьей
- `label3` — показывает, чей сейчас ход
- `button10` — кнопка «Начать заново»

Кнопки расположил в сетке 3×3.

Рабочая сборка:

[TicTacToe.zip](https://github.com/user-attachments/files/34179367/TicTacToe.zip)
