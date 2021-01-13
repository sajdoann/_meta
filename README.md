# ANKI

## JAK SI STÁHNOUT BALÍČEK

- Stáhněte si balíček CrowdAnki:
    - V ANKI: addons → zadejte kód `1788670778` abyste získali addon CrowdAnki a mohli přidávat anki balíčky z GitHubu

        [https://ankiweb.net/shared/info/1788670778](https://ankiweb.net/shared/info/1788670778)

- Importujte balíček pomocí CrowdAnki
    - File → CrowdAnki: import git repository
        - najděte si repozitář, co chcete importovat
            - např [https://github.com/anki-all-stars/Teorie__ZDM.git](https://github.com/anki-all-stars/Teorie__ZDM.git)

        ![ANKI%20f1ecc4c302ba44549cd9e18abdb432f8/Untitled.png](ANKI%20f1ecc4c302ba44549cd9e18abdb432f8/Untitled.png)

    - *Vyberte vše v personal Fields, klidkněte ok (Možná ne we dont know what this does atm)*

        ![ANKI%20f1ecc4c302ba44549cd9e18abdb432f8/Untitled%201.png](ANKI%20f1ecc4c302ba44549cd9e18abdb432f8/Untitled%201.png)

## JAK NAHRÁT BALÍČEK

- Dodržujte formát názvu: [Teorie/Cviceni]::[předmět] (ostatní školy krom FIT ČVUT s prefixem)
    - Například Teorie::ZNS

- Dodržujte tagování balíčků!
    - Tag by měl obsahovat název předmětu, týden a název prezentace, například: ZNS-01-úvod

- Expotujte balíček do Crowd Anki uložte si ho do libovolné SLOŽKY

- Vytvořte nový repozitář se **stejným jménem** jako váš anki balíček
    - Používejte `_` místo `:` tj Teorie\_\_ZNS
    - Nepřidávejte žádné další soubory
            ![ANKI%20f1ecc4c302ba44549cd9e18abdb432f8/Untitled%202.png](ANKI%20f1ecc4c302ba44549cd9e18abdb432f8/Untitled%202.png)
- Otevřete linuxový terminál ve složce ve SLOŽCE

    ```bash
    git init
    git add .
    git commit -m "added anki package Teorie::ZNS"  
    git branch -M main
    git remote add origin git@github.com:anki-all-stars/Teorie__ZNS.gitgit push -u origin main
    ```

    - Pokud nemáte přístup k Linux terminálu, je tento krok možné provést i jinak, více se dozvíte na stránce addonu

## Názvy balíčků:

- Název se skládá z typu balíčku (Teorie/Cvika) a předmětu bez jakýchkoli zbytečných symbolů (Např. Teorie::ZNS nebo Cvika::ZDM)
