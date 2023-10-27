# LJ-Crawler
## Описание
__LJ-Crawler__ - это высокоэффективный инструмент для сбора данных из лингвистических журналов, публикуемых на различных научных платформах. Проект создан для унификации и автоматизации процесса сбора аннотаций публикаций из области лингвистики с их метаданными.

## Особенности
- Универсальный сбор данных: одинаковая структура кода для сбора информации с различных сайтов.
- Автоматизированный сбор статей, исследований и других публикаций из лингвистических журналов.
- Возможность масштабирования и добавления новых источников без изменения основного кода краулера.

## Структура проекта
Ниже представлена структура файлов в репозитории, чтобы вы могли легко навигировать и понимать, как устроен проект.

```
LJ-Crawler/
│
├── README.md                           - Описание проекта и инструкции по его использованию.
├── crawler.ipynb                       - Jupyter Notebook с демонстрацией функционала краулера.
├── requirements.txt                    - Список зависимостей Python, необходимых для работы краулера.
│
└── results/                            - Папка с результатами сбора данных.
    ├── PR_Australian-Journal-of-Linguistics.csv          - Данные из Australian Journal of Linguistics.
    ├── PR_Constructions-and-Frames.csv                    - Данные из Constructions and Frames.
    ├── PR_International-Journal-of-Corpus-Linguistics.csv - Данные из International Journal of Corpus Linguistics.
    ├── PR_International-Journal-of-Multilingualism.csv    - Данные из International Journal of Multilingualism.
    ├── PR_Journal-of-African-Languages-and-Linguistics.csv- Данные из Journal of African Languages and Linguistics.
    ├── PR_Journal-of-Chinese-Linguistics.csv              - Данные из Journal of Chinese Linguistics.
    ├── PR_Journal-of-Pidgin-and-Creole-Languages.csv      - Данные из Journal of Pidgin and Creole Languages.
    ├── PR_Language-and-Cognition.csv                      - Данные из Language and Cognition.
    ├── PR_Open-Linguistics.csv                            - Данные из Open Linguistics.
    └── PR_Research-in-Language.csv                        - Данные из Research in Language.
```

## Требования
- Python 3.x
- Установленные зависимости из файла __requirements.txt__

## Jupyter Notebook
В репозитории присутствует файл __crawler.ipynb_, который содержит примеры использования LJ-Crawler. Этот ноутбук может быть полезен для понимания внутренней работы краулера и предоставляет примеры того, как можно взаимодействовать с краулером и анализировать собранные данные.

### Использование
Для просмотра и использования Jupyter Notebook, пожалуйста, выполните следующие шаги:

1. Убедитесь, что у вас установлен Jupyter Notebook (или вы можете использовать JupyterLab). Если нет, вы можете установить его, используя:
```bash
pip install notebook
```
2. Перейдите в директорию проекта через командную строку и запустите сервер Jupyter Notebook:
```bash
cd путь_к_вашему_репозиторию
jupyter notebook
```
3. В открывшемся в вашем браузере окне Jupyter Notebook навигируйте к crawler.ipynb и откройте его, кликнув по имени файла.
Теперь вы можете просматривать содержимое ноутбука и запускать ячейки кода по мере необходимости, чтобы увидеть демонстрацию в действии.
