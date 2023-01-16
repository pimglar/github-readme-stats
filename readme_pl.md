<p align="center">
 <img width="100px" src="https://res.cloudinary.com/anuraghazra/image/upload/v1594908242/logo_ccswme.svg" align="center" alt="GitHub Readme Stats" />
 <h2 align="center">GitHub Readme Stats</h2>
 <p align="center">Dynamicznie generowane statystyki GitHuba we własnym README</p>
</p>
  <p align="center">
    <a href="https://github.com/anuraghazra/github-readme-stats/actions">
      <img alt="Tests Passing" src="https://github.com/anuraghazra/github-readme-stats/workflows/Test/badge.svg" />
    </a>
    <a href="https://codecov.io/gh/anuraghazra/github-readme-stats">
      <img src="https://codecov.io/gh/anuraghazra/github-readme-stats/branch/master/graph/badge.svg" />
    </a>
    <a href="https://github.com/anuraghazra/github-readme-stats/issues">
      <img alt="Issues" src="https://img.shields.io/github/issues/anuraghazra/github-readme-stats?color=0088ff" />
    </a>
    <a href="https://github.com/anuraghazra/github-readme-stats/pulls">
      <img alt="GitHub pull requests" src="https://img.shields.io/github/issues-pr/anuraghazra/github-readme-stats?color=0088ff" />
    </a>
    <br />
    <br />
    <a href="https://a.paddle.com/v2/click/16413/119403?link=1227">
      <img src="https://img.shields.io/badge/Supported%20by-VSCode%20Power%20User%20%E2%86%92-gray.svg?colorA=655BE1&colorB=4F44D6&style=for-the-badge"/>
    </a>
    <a href="https://a.paddle.com/v2/click/16413/119403?link=2345">
      <img src="https://img.shields.io/badge/Supported%20by-Node%20Cli.com%20%E2%86%92-gray.svg?colorA=61c265&colorB=4CAF50&style=for-the-badge"/>
    </a>
  </p>
  
   <p align="center">
    <a href="#démo">Zobacz demo</a>
    ·
    <a href="https://github.com/anuraghazra/github-readme-stats/issues/new/choose">Zgłoś buga</a>
    ·
    <a href="https://github.com/anuraghazra/github-readme-stats/issues/new/choose">Zaproponuj funkcję</a>
  </p>
  <p align="center">
    <a href="/docs/readme_fr.md">Français</a>
    ·
    <a href="/docs/readme_cn.md">简体中文</a>
    ·
    <a href="/docs/readme_es.md">Español</a>
    ·
    <a href="/docs/readme_de.md">Deutsch</a>
    ·
    <a href="/docs/readme_ja.md">日本語</a>
    ·
    <a href="/docs/readme_pt-BR.md">Português Brasileiro</a>
    ·
    <a href="/docs/readme_it.md">Italiano</a>
    ·
    <a href="/docs/readme_pl.md">Polski</a>
    ·
    <a href="/docs/readme_kr.md">한국어</a>
    ·
    <a href="/docs/readme_nl.md">Nederlands</a>
    ·
    <a href="/docs/readme_np.md">नेपाली</a>
  </p>
</p>
<p align="center">Lubisz ten projekt? Rozważ przekazanie <a href="https://www.paypal.me/anuraghazra">darowizny</a>, aby pomóc w jego ulepszeniu!
  
# Funkcje
  
  -   [GitHub Stats Card](#github-stats-card)
-   [GitHub Extra Pins](#github-extra-pins)
-   [Top Languages Card](#top-languages-card)
-   [Wakatime Week Stats](#wakatime-week-stats)
-   [Themes](#themes)
    -   [Responsive Card Theme](#responsive-card-theme)
-   [Customization](#customization)
    -   [Common Options](#common-options)
    -   [Stats Card Exclusive Options](#stats-card-exclusive-options)
    -   [Repo Card Exclusive Options](#repo-card-exclusive-options)
    -   [Language Card Exclusive Options](#language-card-exclusive-options)
    -   [Wakatime Card Exclusive Option](#wakatime-card-exclusive-options)
-   [Deploy Yourself](#deploy-on-your-own-vercel-instance)
    - [Keep your fork up to date](#keep-your-fork-up-to-date)   
  
  # GitHub Stats Card
  
  Wklej to do swojego markdown i tyle. Proste!
  
  Zmien wartość `?username=` do swojej nazwy na GitHubie.
  
  ```md
  [![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra)](https://github.com/anuraghazra/github-readme-stats)
  ```
  
  > **Uwaga**
  > Dostępne ranki to S+ (top 1%), S (top 25%), A++ (top 45%), A+ (top 60%), oraz B+ (wszyscy). Wartości są obliczane za pomocą [funkcji Dystrybuanta](https://pl.wikipedia.org/wiki/Dystrybuanta) 
  używając liczby zatwierdzień, wkładów, problemów, gwiazdek, pull requesty, obserwujących oraz posiadanych repozytoriów. Implementacja może zostać zbadana pod linkiem [src/calculateRank.js](./src/calculateRank.js).
        
### Konkretne ukrycie statystyk
        
Dodaj wartość `&hide=`, aby ukryć konkretną statystykę.
        
> Opcje: `&hide=stars,commits,prs,issues,contribs`

```md
![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&hide=contribs,prs)
```        
        
### Wliczanie do statystyk prywatnych repozytoriów        
        
Do swoich statystyk możesz dodać swoje prywatne repozytoria używając wartości `&count_private=true`.         
        
> **Uwaga**        
Jeżeli wdrażasz ten projekt samodzielnie, prywatne repozytoria będą domyślnie zliczane. Jeśli używasz z publicznej instancji Vercela, musisz wybrać opcję [udostępnij twoje prywatne repozytoria](https://docs.github.com/en/account-and-profile/setting-up-and-managing-your-github-profile/managing-contribution-settings-on-your-profile/showing-your-private-contributions-and-achievements-on-your-profile).       
        
> Opcje : `&count_private=true` 
	
```md
![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&count_private=true)
```
	
### Pokazywanie ikon
	
Aby pokazać ikony w statystykach, należy dodać wartość `show_icons=true` jak:
	
```md
![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true)
```

### Motywy
        
Ze wbudowanymi motywami, możesz dostosować wygląd statystyk bez konieczności jakichkolwiek [manualnych dostosowań](#customization).
	
Użyj wartości `&theme=THEME_NAME` w ten sposób:

```md
![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true&theme=radical)
```
	
### Wszystkie wbudowane motywy
	
GitHub Readme ma w swobie kilka wbudowanych motywów (np. `dark`, `radical`, `merko`, `gruvbox`, `tokyonight`, `onedark`, `cobalt`, `synthwave`, `highcontrast`, `dracula`).
	
<img src="https://res.cloudinary.com/anuraghazra/image/upload/v1595174536/grs-themes_l4ynja.png" alt="GitHub Readme Stats Themes" width="600px"/>
	
Możesz zobaczyć podgląd [wszystkich dostępnych motywów](./themes/README.md) lub zobaczyć [plik config motywów](./themes/index.js) oraz **sam możesz stworzyć nowe motywy** jeżeli chcesz :D

#### Responsywny motyw statystyk
	
[![Anurag's GitHub stats-Dark](https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true&theme=dark#gh-dark-mode-only)](https://github.com/anuraghazra/github-readme-stats#gh-dark-mode-only)
[![Anurag's GitHub stats-Light](https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true&theme=default#gh-light-mode-only)](https://github.com/anuraghazra/github-readme-stats#gh-light-mode-only)
	
Ponieważ GitHub będzie ponownie ładował statystyki i działał na ich [CDN'ach](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/about-anonymized-urls) nie możemy wpływać na motyw przeglądarki/GitHub po stronie serwera. Istnieją jednak cztery metody, których można użyć do tworzenia motywów dynamiki po stronie klienta.
	
##### Użycie przezroczystego motywu 

Dodaliśmy `transparent` motyw z przezroczystym tłem. Ten motyw jest zoptymalizowany, aby działać dobrze na ciemnym i jasnym motywie GitHuba. Motyw można aktywować dodając parametr `&theme=transparent` w ten sposób:

```md
![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true&theme=transparent)
```
	
<details>
<summary>:eyes:Pokaż przykład</summary>

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true&theme=transparent)

</details>

##### Dodanie przezroczystego kanału alfa do motywu koloru tła

Możesz ustawić parametr `bg_color`, aby zrobić [dostępne motywy](./themes/README.md) przezroczyste. Działa to w ten sposób, że ustawia się `bg_color` na kolor z przezroczystym kanałem alfa (np. `bg_color=000000`):
	
```md
![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true&bg_color=00000000)
```
	
	
<details>
<summary>:eyes:Pokaż przykład</summary>

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true&bg_color=00000000)

</details>
