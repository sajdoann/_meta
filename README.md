# ANKI

## JAK SI STÁHNOUT BALÍČEK

- stáhněte si balíček CrowdAnki:
    - V ANKI: addons → zadejte kód 1788670778 abyste získali CrowdAnki: JSON export&import addon a tak mohli přidávat anki balíčky z gitu

        [https://ankiweb.net/shared/info/1788670778](https://ankiweb.net/shared/info/1788670778)

- importujte balíček pomocí CrowdAnki
    - File → CrowdAnki: import git repository
        - najděte si repozitář, co chcete importovat
            - např [https://github.com/anki-all-stars/Teorie__ZDM.git](https://github.com/anki-all-stars/Teorie__ZDM.git)

        ![ANKI%20f1ecc4c302ba44549cd9e18abdb432f8/Untitled.png](ANKI%20f1ecc4c302ba44549cd9e18abdb432f8/Untitled.png)

    - vyberte vše v personal Fields, klidkněte ok

        ![ANKI%20f1ecc4c302ba44549cd9e18abdb432f8/Untitled%201.png](ANKI%20f1ecc4c302ba44549cd9e18abdb432f8/Untitled%201.png)

## JAK NAHRÁT BALÍČEK

- dodržujte formát názvu: [Teorie/Cviceni]::[předmět] (ostatní školy krom FIT ČVUT s prefixem)
    - např Teorie::ZNS
    - otagujte všechny přednášky! předmět_týden_název-přednášky např ZNS-01-uvod
- expotujte balíček do Crowd Anki uložte si ho do nějaké SLOŽKY
- vytvořte nový repozitář se stejným jménem jako váš anki balíček
    - používejte _ místo : tj Teorie__ZNS
        - tj Teorie__ZNS

            ![ANKI%20f1ecc4c302ba44549cd9e18abdb432f8/Untitled%202.png](ANKI%20f1ecc4c302ba44549cd9e18abdb432f8/Untitled%202.png)

    - nepřidávejte žádné další soubory
- ve SLOŽCE

    ```jsx
    git init
    git commit -m "added anki package Teorie::ZNS"  
    git branch -M main
    git remote add origin git@github.com:anki-all-stars/Teorie__ZNS.gitgit push -u origin main
    ```

## NÁZVY:

- předměty
    - teorie
    - příklady