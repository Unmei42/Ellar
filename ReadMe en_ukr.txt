========================
         openSMILE GUI
========================

A simple graphical interface for launching SMILExtract.exe with options to select an input WAV file and save the result as CSV.

Features:
- WAV file selection
- Choose folder for saving CSV output
- Automatically generates a CSV file name
- Remembers selected paths and window size across sessions (stored in settings.json)
- Button to open the result folder

Requirements:
- Python 3.x
- Tkinter (part of the standard library)

Folder structure:
project/
├── wav-to-text.py        <- main GUI code
├── settings.json         <- created automatically
├── config/
│   └── egemaps/v02/eGeMAPSv02.conf
├── build/
│   └── progsrc/smilextract/SMILExtract.exe

Run:
python wav-to-text.py

LICENSE:
This project is freely distributed under the following conditions:

- You may use, modify, and redistribute it in **non-commercial or conditional commercial** projects **only if a free version is always available to the public**.
- You must retain author credit: "idea by Unmei42" (in README, UI, or source code comments).

This project includes SMILExtract.exe from openSMILE (Apache 2.0). See NOTICE.txt for details.


The credit may be minimal or textual, but must be visible when reviewing the source or interface.

---

Need help interpreting the results?  
Try the linked GPT assistant created for this project: https://chatgpt.com/share/6822471b-b5f8-800e-9616-103d5bb903ae

---

We welcome contributions — improve the UI, expand functionality, or adapt it to your needs.

========================
         openSMILE GUI
========================

Проста графічна оболонка для запуску SMILExtract.exe з можливістю вибору вхідного WAV-файлу та збереження результату в CSV.

Можливості:
- Вибір аудіофайлу у форматі WAV
- Вказівка папки для збереження результату
- Автоматичне формування імені CSV-файлу
- Збереження шляхів і розміру вікна між запусками (у settings.json)
- Кнопка для відкриття папки з результатом

Вимоги:
- Python 3.x
- Tkinter (входить до стандартної бібліотеки)

Структура папок:
project/
├── wav-to-text.py        <- основний код GUI
├── settings.json         <- створюється автоматично
├── config/
│   └── egemaps/v02/eGeMAPSv02.conf
├── build/
│   └── progsrc/smilextract/SMILExtract.exe

Запуск:
python wav-to-text.py

ЛІЦЕНЗІЯ:
Проєкт поширюється вільно за наступних умов:

- Ви можете використовувати, змінювати та поширювати його у некомерційних або умовно комерційних проєктах **лише за наявності вільної версії, доступної публічно**.
- Обов’язкове зазначення авторства: "idea by Unmei42" (у README, UI або коментарях до коду).

Цей проєкт включає SMILExtract.exe з пакету openSMILE (ліцензія Apache 2.0). Докладно — у NOTICE.txt.


Підпис може бути текстовим, ненав’язливим, але повинен бути помітним при перегляді вихідного коду або інтерфейсу.

---

Потрібна допомога з інтерпретацією результатів?  
Скористайся GPT-помічником, створеним спеціально для цього проєкту: https://chatgpt.com/share/6822471b-b5f8-800e-9616-103d5bb903ae

---

Запрошуємо до участі — покращуйте інтерфейс, розширюйте функціональність, адаптуйте під себе.
