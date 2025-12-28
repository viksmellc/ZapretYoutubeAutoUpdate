# ZapretYoutubeAutoUpdate
**ZapretYoutubeAutoUpdate** — automatic download and launch of *zapret-discord-youtube*

This program:
- Downloads the latest version from GitHub (if not already downloaded),
- Extracts it into a version-numbered folder (e.g., `1.9.1`),
- Runs the specified `.bat` file **as administrator**.

──────────────────────────────────────────────────────  
**How to use:**

1. Simply run the program — the default file will be used:  
  `ZapretYoutubeAutoUpdate.exe`  
  → Launches: `general (FAKE TLS AUTO).bat`

2. To run a different `.bat` file, pass its name as a command-line argument:  
  `ZapretYoutubeAutoUpdate.exe "general (ALT2).bat"`  

  → The filename must exactly match a file inside:  
   `[version]\zapret-discord-youtube-main\[filename.bat]`  

  Examples:  
  `ZapretYoutubeAutoUpdate.exe "general (ALT1).bat"`  
  `ZapretYoutubeAutoUpdate.exe "general (ALT2).bat"`  

──────────────────────────────────────────────────────  
**Important notes:**
- Administrator privileges (UAC prompt) are required on first run.
- All files are saved in the current directory (next to the `.exe`).
- If the version folder already exists, no re-download occurs.

**Author:** [Elena.Me / SiaGlobe]  
https://vk.com/ai_buka_me  
**Version:** 1.1


ZapretYoutubeAutoUpdate — автоматическая загрузка и запуск zapret-discord-youtube

Эта программа:
- Скачивает актуальную версию из GitHub (если ещё не загружена),
- Распаковывает её в папку с номером версии (например, "1.9.1"),
- Запускает указанный .bat-файл от имени администратора.

──────────────────────────────────────────────────────
Как использовать:

1. Просто запустите программу — будет использован файл по умолчанию:
      ZapretYoutubeAutoUpdate.exe

   ➜ Запускается: general (FAKE TLS AUTO).bat

2. Чтобы запустить другой .bat-файл, передайте его имя как аргумент:
      ZapretYoutubeAutoUpdate.exe "general (ALT2).bat"

   ➜ Имя файла должно совпадать с именем в папке:
      [версия]\zapret-discord-youtube-main\[имя.bat]

   Примеры:
      ZapretYoutubeAutoUpdate.exe "general (ALT1).bat"
      ZapretYoutubeAutoUpdate.exe "general (ALT2).bat"

──────────────────────────────────────────────────────
Важно:
- При первом запуске потребуются права администратора (UAC).
- Все файлы сохраняются в текущей папке (рядом с .exe).
- Если папка версии уже есть — повторная загрузка НЕ выполняется.

Автор: [Elena.Me / SiaGlobe] 
https://vk.com/ai_buka_me 
Версия: 1.1
