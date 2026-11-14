# OpenByte 🛡️

**Lightweight, free and open-source antivirus. 100% non-profit.**

OpenByte is an antivirus that doesn't slow down your PC. Built on SHA256 hashes, with a cloud database updated by the community.

> **Zero profit.** The author takes $0 from this project. All donations go only to servers.

🌐 Website: **https://openbyte.is-a.dev**

---

## ✨ Why OpenByte?

- **Lightweight** - doesn't eat RAM like Kaspersky or ESET
- **Fast** - scans only SHA256 hashes, not whole files
- **Update in 0.1s** - only diff (50KB), not 500MB
- **Secure** - every update is digitally signed
- **Open-source** - anyone can audit the code, no hidden spyware

## 🧠 How it works?

1. **Ghost** scans your PC and calculates SHA256 of files
2. Sends hash to OpenByte Cloud
3. Cloud answers: `CLEAN` / `MALICIOUS` / `UNKNOWN`
4. If it's a new virus, hash goes to all users in < 15 minutes

    You catch a virus -> You send SHA256 -> Server verifies -> Everyone gets update

## 🚀 Install

    git clone https://github.com/your-nick/openbyte.git
    cd openbyte
    # Windows build coming soon

## 🤝 Support - no profit for author

OpenByte is non-profit. If you want to help, your donation goes only to servers and domain.

- GitHub Sponsors - soon
- Ko-fi - soon
- Open Collective - transparent, everyone sees expenses

## 🗺️ Roadmap

- [x] Idea + name OpenByte
- [x] Domain openbyte.is-a.dev
- [ ] Ghost - SHA256 scanning engine
- [ ] Cloud API on Oracle Free
- [ ] Auto-update SHA256 DB for everyone
- [ ] First version for Windows

## 📜 License

GNU General Public License v3.0 - free software, stay free.

---
Made with ❤️ in Poland. No profit, just protection.

---

# OpenByte 🛡️ [RU]

**Легкий, бесплатный и open-source антивирус. 100% non-profit.**

OpenByte - антивирус, который не тормозит твой ПК. Построен на SHA256 хэшах, с облачной базой, обновляемой сообществом.

> **Ноль прибыли.** Автор не берет с этого проекта ни копейки. Все донаты идут только на сервера.

🌐 Сайт: **https://openbyte.is-a.dev**

---

## ✨ Почему OpenByte?

- **Легкий** - не жрет RAM как Касперский или ESET
- **Быстрый** - сканирует только SHA256 хэши, а не целые файлы
- **Обновление за 0.1с** - только разница (50КБ), а не 500МБ
- **Безопасный** - каждое обновление с цифровой подписью
- **Open-source** - любой может проверить код, никакого скрытого шпиона

## 🧠 Как это работает?

1. **Ghost** сканирует твой ПК и считает SHA256 файлов
2. Отправляет хэш в облако OpenByte
3. Облако отвечает: `CLEAN` / `MALICIOUS` / `UNKNOWN`
4. Если это новый вирус, хэш улетает всем пользователям за < 15 минут

    Ты поймал вирус -> Отправил SHA256 -> Сервер проверил -> Все получили обновление

## 🚀 Установка

    git clone https://github.com/your-nick/openbyte.git
    cd openbyte
    # Сборка для Windows скоро

## 🤝 Поддержать - без прибыли для автора

OpenByte - non-profit. Если хочешь помочь, твой донат пойдет только на сервера и домен.

- GitHub Sponsors - скоро
- Ko-fi - скоро
- Open Collective - прозрачная касса, все видят расходы

## 🗺️ Roadmap

- [x] Идея + название OpenByte
- [x] Домен openbyte.is-a.dev
- [ ] Ghost - движок сканирования SHA256
- [ ] Cloud API на Oracle Free
- [ ] Авто-обновление базы SHA256 для всех
- [ ] Первая версия для Windows

## 📜 Лицензия

GNU General Public License v3.0 - свободное ПО, остается свободным.

---
Сделано с ❤️ в Польше. Никакой прибыли, только защита.
