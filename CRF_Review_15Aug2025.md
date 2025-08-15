{\rtf1\ansi\ansicpg1250\cocoartf2822
\cocoatextscaling0\cocoaplatform0{\fonttbl\f0\fswiss\fcharset0 Helvetica;}
{\colortbl;\red255\green255\blue255;}
{\*\expandedcolortbl;;}
\paperw11900\paperh16840\margl1440\margr1440\vieww11520\viewh8400\viewkind0
\pard\tx720\tx1440\tx2160\tx2880\tx3600\tx4320\tx5040\tx5760\tx6480\tx7200\tx7920\tx8640\pardirnatural\partightenfactor0

\f0\fs24 \cf0 | Temat         | Opis                                   | Przyk\uc0\u322 ad kodu / Dzia\u322 anie                       |\
|---------------|----------------------------------------|-------------------------------------------------|\
| **Pandas**    | Wczytywanie danych z CSV              | `data = pd.read_csv('/U\uc0\u380 ytkownicy/kingamiller/Dokumenty/Data/heart_disease_uci.csv')` |\
|               | Filtrowanie danych (chol > 240)        | `high_chol = data[data['chol'] > 240]`          |\
|               | Grupowanie i agregacja po p\uc0\u322 ci         | `data.groupby('sex')[['age', 'chol']].mean()`   |\
|               | Obliczanie \uc0\u347 redniej z formatowaniem    | `print(f"\u346 redni wiek: \{avg_age:.2f\}")`          |\
| **SQL**       | Podstawowe zapytania                   | `SELECT * FROM patients LIMIT 5;`               |\
|               | JOIN i podzapytania (z kursu)          | `SELECT a.name FROM a JOIN b ON a.id = b.id;`   |\
| **Git/GitHub**| Nawigacja w Terminalu                  | `cd ~/Dokumenty; cd Data`                       |\
|               | Dodawanie plik\'f3w przez Terminal        | `git add file.ipynb; git commit; git push`      |\
|               | Upload plik\'f3w przez przegl\uc0\u261 dark\u281        | Przeci\u261 gnij plik na github.com/kingamiller/...  |\
| **Markdown**  | Tworzenie tabel i formatowanie         | `| Temat | Opis |` (ta tabela!)                |}