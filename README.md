# ANKI

## Co je ANKI?

Anki je učící nástroj na bázi elektronických kartiček. Studium Anki kartiček probíhá tak, že Vám nejdříve Anki ukáže kartičku poprvé a dále Vám ji ukazuje podle toho jak moc dané téma umíte. Pokud často odpovíte špatně, Anki Vám tu kartičku bude ukazovat třeba každých pár dnů. Pokud na kartičku odpovídáte dobře, Anki Vám ji ukáže jednou za měsíc. Tato metoda učení se nazývá [Spaced Repetition](https://en.wikipedia.org/wiki/Spaced_repetition) a je [obecně považována](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5126970/) za [velmi dobrou](http://psychnet.wustl.edu/coglab/wp-content/uploads/2015/01/2007-Is-expanded.pdf) [metodu](https://www.theguardian.com/education/2016/jan/23/spaced-repetition-a-hack-to-make-your-brain-store-information).

## Proč bych měl používat Anki?

Protože Anki je efektivní. Student nemusí řešit studijní materiály, co se učit, kdy se učit. Prostě si stáhne Anki balíček a zbytek nechá na softwaru.

Protože Anki Vás naučí téma ať chcete nebo ne. Při klasickém učení se může stávat, že student podvědomě obchází věci, kterým nerozumí, to se u Anki stát nemůže, naopak, Anki předhazuje ty témata, která student umí nejméně, nejvíce.

**Protože Anki je šetří čas.** Díky tomu, že Anki studenta neučí to, co už umí, si student opakuje pouze to co potřebuje a na zkoušku jde připraven lépe s menšími časovými investicemi.

## Jak začít?

- 1. Krok - Stáhnout si Anki [zde](https://apps.ankiweb.net/)

- 2. Krok - Stáhnout si doplněk CrowdAnki
	- Tento doplňek zprostředkovává sdílení kartiček
	- V Anki je v hlavním panelu menu `tools`. V něm je manažer addonů: `addons`.
	- V tomto manažeru doplňků probíhá přidání CrowdAnki kliknutím na `Get Add-ons...` a zadáním kódu `1788670778`
	- Více infromací o doplňku se nachází [zde](https://ankiweb.net/shared/info/1788670778)

- 3. Krok - Importujte libovolný předmět!
	- V přehledu předmětů [Předhled.md](Prehled.md) se nachází odkazy na zpracované předměty, u každého se nachází link
		- Například: `https://github.com/anki-all-stars/Teorie__ZDM.git`
	- V aplikaci, v hlavním menu se CrowdAnki nachází pod `File -> CrowdAnki: Import git repository`
	- Po vložení linku z přehledu do `CrowdAnki: Import git repository` a odsouhlasení přednastavených hodnot je k dispozici předmět na lokálním Anki
        ![ANKI%20f1ecc4c302ba44549cd9e18abdb432f8/Untitled.png](ANKI%20f1ecc4c302ba44549cd9e18abdb432f8/Untitled.png)

## Jak přispívat?

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
