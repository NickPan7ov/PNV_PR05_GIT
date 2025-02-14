# Практическая работа №5-6
![Здесь не мое фото😁](https://github.com/NickPan7ov/PNV_PR05_GIT/blob/master/IMG_20250214_104206_058.png)\
*Разработал: Студент группы ИС-21Б*\
***Панфилов Никита***
____
```
Студент Заволжского Автоматорного Техникума
пр. Мира, 18, Заволжье, Нижегородская обл., 606431
```
## Описание программы
ㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤ✅ Программа __предназначена__ для работы с платформой **GITHUB**✅\
✨В данной ___программе___ разработанная на языке ~~1c~~ C# присутствуют для тестирования и добавления последующих изменений.✨\
ㅤㅤㅤㅤㅤㅤㅤㅤㅤ👇Ниже предоставленна подробная информация о программе и репозитории👇
### 1.Версии комитов
Всего коммитов **6**
| Номер коммита | Название коммита | Описание |
|----------------|:---------:|----------------:|
| 1 | 1 commit | Добавление программы в репозиторий|
| 2 | Add AddFormcs | Создание формы добавления |
| 3 | UserName in Form1 | Добавление имени пользователя на главную форму |
| 4 | Add class DB | Добавление класса для работы с бд |
| 5 | PR05_GITTEA | Добавления репозитория на платформу GitTea |
| 6 | add picture | Добавление картинки в репозиторий |
### 2. Код программы
AddForm.cs
```c#
﻿using System;
using System.Collections.Generic;
using System.ComponentModel;
using System.Data;
using System.Drawing;
using System.Linq;
using System.Text;
using System.Threading.Tasks;
using System.Windows.Forms;

namespace PR05_GIT_Panfilov
{
    public partial class AddForm : Form
    {
        public AddForm()
        {
            InitializeComponent();
        }
    }
}
```
AddForm.Designer.cs
```c#
namespace PR05_GIT_Panfilov
{
    partial class AddForm
    {
        /// <summary>
        /// Required designer variable.
        /// </summary>
        private System.ComponentModel.IContainer components = null;

        /// <summary>
        /// Clean up any resources being used.
        /// </summary>
        /// <param name="disposing">true if managed resources should be disposed; otherwise, false.</param>
        protected override void Dispose(bool disposing)
        {
            if (disposing && (components != null))
            {
                components.Dispose();
            }
            base.Dispose(disposing);
        }

        #region Windows Form Designer generated code

        /// <summary>
        /// Required method for Designer support - do not modify
        /// the contents of this method with the code editor.
        /// </summary>
        private void InitializeComponent()
        {
            this.components = new System.ComponentModel.Container();
            this.AutoScaleMode = System.Windows.Forms.AutoScaleMode.Font;
            this.ClientSize = new System.Drawing.Size(800, 450);
            this.Text = "AddForm";
        }

        #endregion
    }
}
```
db.cs
```c#
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace PR05_GIT_Panfilov
{
    class Db
    {
        static void bd()
        {
            double ok;

        }
    }
}
```
### 3. Установка приложения
```
1. Скачать репозиторий через git hub либо через консоль git bush
2. Запустить приложение PR05_GIT_Panfilov.sln
```
#### Дополнительная информация
____
***Ссылка на мою страницу*** [Моя страница github](https://github.com/NickPan7ov) \
***Ссылка на доп. информацию по созданию программы на c#*** https://learn.microsoft.com/ru-ru/visualstudio/get-started/csharp/tutorial-console?view=vs-2022
