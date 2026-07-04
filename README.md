<h1 align="center">Привет 👋 Я Адильжан Кушербай</h1>
 
<h3 align="center">Backend Developer (Go) → AI Engineer in progress</h3>
 
<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=20&pause=1000&color=00D9FF&center=true&vCenter=true&width=600&lines=Go+Developer;Learning+AI+%2B+ML+Engineering;Building+real+projects%2C+not+tutorials" alt="Typing SVG" />
</p>
---
 
### 🚀 О себе
 
- 🎓 Студент **Tomorrow School** (Astana Hub) — практическая peer-to-peer школа разработки
- 💻 Начал с **Go**: системное программирование, backend, REST API, concurrency
- 🧠 Сейчас двигаюсь в сторону **AI-инженерии**: Python, FastAPI, LLM-интеграции, ML-основы
- 🌍 Базируюсь в Астане, Казахстан
- 🎯 Цель: стать инженером, который умеет **строить продукты** и **встраивать в них AI**, а не просто теоретизировать
---
 
### 🛠️ Стек технологий
 
**Языки:**
![Go](https://img.shields.io/badge/-Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
 
**Backend & Инфраструктура:**
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![SQLite](https://img.shields.io/badge/-SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![FastAPI](https://img.shields.io/badge/-FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
 
**AI/ML (в процессе освоения):**
![OpenAI](https://img.shields.io/badge/-OpenAI%20API-412991?style=flat-square&logo=openai&logoColor=white)
![NumPy](https://img.shields.io/badge/-NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
 
**Инструменты:**
![Git](https://img.shields.io/badge/-Git-F05032?style=flat-square&logo=git&logoColor=white)
![VS Code](https://img.shields.io/badge/-VS%20Code-007ACC?style=flat-square&logo=visualstudiocode&logoColor=white)
![Linux](https://img.shields.io/badge/-Linux%2FWSL-FCC624?style=flat-square&logo=linux&logoColor=black)
 
---
 
### 📌 Ключевые проекты
 
<!-- Замените ССЫЛКА на реальные ссылки после публикации репозиториев -->
 
| Проект | Описание | Стек |
|---|---|---|
| [groupie-tracker](https://github.com/adilzhan-dev/groupie-tracker) | Веб-приложение с визуализацией данных о музыкальных артистах через внешний API | Go, HTML/CSS |
| [ascii-art-web](https://github.com/adilzhan-dev/ascii-art-web) | ASCII-art генератор с веб-интерфейсом на Go | Go, HTML/CSS |
# ASCII Art

A command-line tool that converts text input into large graphic representations using ASCII characters (banner-style text art).

## 📖 Description

ASCII Art reads a string argument from the command line, maps each character to its multi-line ASCII banner equivalent (using the `standard` font), and prints the full output to the terminal. The program handles a wide range of input cases, including whitespace, punctuation, mixed case, and explicit newline sequences (`\n`) passed as literal text.

## 🎯 Key Features

- Converts arbitrary text into ASCII banner art
- Supports the full standard ASCII printable character range
- Handles multiple arguments and literal `\n` sequences as line breaks
- Gracefully ignores characters outside the supported font range (e.g. Cyrillic)

## 🛠️ Technologies

- Go (standard library only)

## 🚀 Usage

```bash
go run . "Hello World"
go run . "Hello\nThere"
go run . "1a\"#FdwHywR&/()="
```

Additional usage examples:

```bash
go run . "" | cat -e
go run . "\n" | cat -e
go run . "Hello\n" | cat -e
go run . "hello" | cat -e
go run . "HeLlO" | cat -e
go run . "Hello There" | cat -e
go run . "1Hello 2There" | cat -e
go run . "Hello\n\nThere" | cat -e
go run . hello
go run . HELLO
go run . "{Hello & There #}"
go run . "{|}~"
go run . "[\]^_ 'a"
go run . ":;<=>?@"
go run . abcdefghijklmnopqrstuvwxyz
go run . "ABCDEFGHIJKLMNOPQRSTUVWXYZ"
```

## ⚙️ Implementation Notes

- Only one font is used at this stage (`standard.txt`)
- Characters not defined in the font template (e.g. Cyrillic letters) are intentionally ignored
- A special case is handled for the literal `\n` sequence passed within a single argument (as an alternative to passing multiple separate arguments) to trigger a line break. Some edge-case side effects of this approach (e.g. printing the literal text `\n` instead of a line break in specific combinations) were identified but left unresolved at this stage, as they fall outside the project's core requirements.

## 📂 Project Structure

```
ascii-art/
├── main.go
├── standard.txt      # font template
└── go.mod
```

## ⚠️ Known Limitations

Educational project built as part of the Tomorrow School (Astana Hub) curriculum — focused on file parsing, string/rune manipulation, and pattern matching in Go rather than production use.

## 👤 Authors

- Adilzhan Kusherbay ([@adilzhan-dev](https://github.com/adilzhan-dev))

## 📄 License

MIT

 
---
 
### 📈 Текущий фокус
 
- 🔨 Прохождение Go-модуля Tomorrow School: HTTP-серверы, форумы, сети, concurrency
- 📚 Параллельно подтягиваю линейную алгебру и статистику для будущего ML-этапа
- 🎯 В процессе поиска junior Go developer позиции в Астане/Алматы
---
 
### 📫 Связаться со мной
 
<!-- Замените ССЫЛКА на реальные адреса -->
[![LinkedIn](https://img.shields.io/badge/-LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](ССЫЛКА)
[![Telegram](https://img.shields.io/badge/-Telegram-26A5E4?style=flat-square&logo=telegram&logoColor=white)](ССЫЛКА)
 
---
 
<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=adilzhan-dev&show_icons=true&theme=tokyonight" alt="GitHub Stats" />
</p>
