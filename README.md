<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:000000,60:003B00,100:00FF41&height=210&section=header&text=KAVI%20KRUIZZ&fontSize=54&fontColor=00FF41&fontAlignY=40&desc=%5B%20ACCESS%20GRANTED%20%5D&descAlignY=62&descSize=17&animation=twinkling" alt="Kavi KruizZ" width="100%" />

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=17&duration=2700&pause=900&color=00FF41&center=true&vCenter=true&width=720&height=45&lines=root%40kavikruizz%3A~%23+whoami;Software+Developer+%7C+Java+%7C+Web+%7C+Android;Decode.+Disrupt.+Rewrite.;Build+successful.+Exit+code%3A+0" alt="Animated terminal introduction" />

<p>
<img src="https://komarev.com/ghpvc/?username=kavikruizz&style=flat-square&color=00FF41&labelColor=000000&label=VISITORS" alt="Profile views" />
<a href="https://github.com/kavikruizz?tab=followers"><img src="https://img.shields.io/github/followers/kavikruizz?style=flat-square&logo=github&label=FOLLOWERS&labelColor=000000&color=00FF41" alt="Followers" /></a>
<img src="https://img.shields.io/badge/STATUS-BUILDING-00FF41?style=flat-square&labelColor=000000" alt="Currently building" />
</p>

</div>

---

### `root@kavikruizz:~# whoami`

```text
ALIAS       : KaviKruizZ
ROLE        : Software Developer
FOCUS       : Java Desktop | Full-Stack Web | Android
PRINCIPLES  : Clean architecture. Thoughtful UI. Reliable systems.
STATUS      : Learning, building, and refining.
```

I design and develop practical software solutions, from **Java Swing POS and inventory management systems** to **full-stack e-commerce platforms** and **Android applications**. My focus is on clean architecture, reliable data management, and intuitive user experiences that simplify complex business workflows.

### `root@kavikruizz:~# ./load_modules.sh`

```text
[ OK ] desktop  ........ Java · Swing · JDBC
[ OK ] web      ........ HTML · CSS · JavaScript · PHP · Next.js
[ OK ] mobile   ........ Android Studio · Java · SQLite
[ OK ] data     ........ MySQL · MongoDB · Firebase
[ OK ] tooling  ........ Git · GitHub · VS Code · NetBeans · Figma · Docker
```

<div align="center">

<img src="https://skillicons.dev/icons?i=java,js,php,html,css,nextjs,mysql,mongodb,firebase,sqlite,androidstudio,git,github,vscode,figma,docker&theme=dark&perline=8" alt="Developer technology stack" />

</div>

---

### `root@kavikruizz:~# tree projects/`

```text
projects/
├── LedgerOne/     # Restaurant POS & Inventory Management
├── Luxe/          # Fashion E-Commerce Platform
└── RecipeBox/     # Android Recipe Manager
```

<table>
<tr>
<td width="50%" valign="top">

#### `[01] LedgerOne`
**Restaurant POS & Inventory Management**

A Java Swing desktop application for café operations, sales, inventory, and reporting.

```text
+ role-based authentication
+ POS, payment & receipts
+ cancellations & partial refunds
+ recipe-based stock deduction
+ inventory movements & reports
```

<a href="https://github.com/kavikruizz/LedgerOne">
  <img src="https://raw.githubusercontent.com/kavikruizz/LedgerOne/main/screenshots/02-dashboard.png" alt="LedgerOne Dashboard Preview" width="100%" />
</a>


<img src="https://img.shields.io/badge/Java-000000?style=flat-square&logo=openjdk&logoColor=00FF41" alt="Java" />
<img src="https://img.shields.io/badge/Swing-000000?style=flat-square&logoColor=00FF41" alt="Swing" />
<img src="https://img.shields.io/badge/MySQL-000000?style=flat-square&logo=mysql&logoColor=00FF41" alt="MySQL" />

<a href="https://github.com/kavikruizz/LedgerOne">
  <b>⚡ Explore LedgerOne →</b>
</a>

</td>
<td width="50%" valign="top">

#### `[02] Luxe`
**Fashion E-Commerce Platform**

A responsive online shopping experience with customer storefront and admin tools.

```text
+ product browsing & discovery
+ shopping cart & checkout
+ customer account management
+ administration dashboard
+ database-backed operations
```

<img src="https://img.shields.io/badge/HTML-000000?style=flat-square&logo=html5&logoColor=00FF41" alt="HTML" />
<img src="https://img.shields.io/badge/CSS-000000?style=flat-square&logo=css3&logoColor=00FF41" alt="CSS" />
<img src="https://img.shields.io/badge/JavaScript-000000?style=flat-square&logo=javascript&logoColor=00FF41" alt="JavaScript" />
<img src="https://img.shields.io/badge/PHP-000000?style=flat-square&logo=php&logoColor=00FF41" alt="PHP" />
<img src="https://img.shields.io/badge/MySQL-000000?style=flat-square&logo=mysql&logoColor=00FF41" alt="MySQL" />

<a href="https://github.com/kavikruizz?tab=repositories"><b>Explore repositories →</b></a>

</td>
</tr>
</table>

<details>
<summary><b><code>cat ./LedgerOne/architecture.md</code> — view system architecture</b></summary>

```mermaid
flowchart LR
    UI["Swing UI<br/>Login · POS · Inventory · Reports"] --> SVC["Service Layer<br/>Business rules & transactions"]
    SVC --> DAO["DAO Layer<br/>JDBC"]
    DAO --> DB[(MySQL)]
    SVC --> RCP["Recipe & Inventory Logic"]
    RCP --> DAO
```

```text
sale()   -> record order -> resolve recipe -> deduct ingredients
refund() -> validate paid order -> record refund -> log prepared-food waste
```

**Inventory rule:** Prepared-food refunds do not restore usable ingredient stock. Stock reversals apply only when appropriate, such as qualifying cancellations before preparation.

</details>

---

### `root@kavikruizz:~# cat principles.conf`

```ini
[engineering]
structure_first   = true
user_centred_ui   = true
data_integrity    = true
ship_then_refine  = true

[mindset]
discipline        = constant
curiosity         = unlimited
execution         = deliberate
```

---

### `root@kavikruizz:~# git stats --overview`

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=kavikruizz&show_icons=true&hide_border=true&bg_color=000000&title_color=00FF41&text_color=9FE5AE&icon_color=00FF41" alt="GitHub statistics" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=kavikruizz&layout=compact&hide_border=true&bg_color=000000&title_color=00FF41&text_color=9FE5AE" alt="Most-used public repository languages" />

<img src="https://streak-stats.demolab.com?user=kavikruizz&hide_border=true&background=000000&stroke=003B00&ring=00FF41&fire=00FF41&currStreakLabel=00FF41&sideLabels=9FE5AE&dates=008F11&sideNums=00FF41&currStreakNum=00FF41" alt="GitHub contribution streak" />

</div>

---

### `root@kavikruizz:~# ./connect.sh`

Open to collaboration, freelance projects, and interesting engineering challenges.

<div align="center">

<a href="mailto:kavikruizz1@gmail.com"><img src="https://img.shields.io/badge/EMAIL-CONTACT-003B00?style=for-the-badge&logo=gmail&logoColor=00FF41&labelColor=000000" alt="Email" /></a>
<a href="https://github.com/kavikruizz"><img src="https://img.shields.io/badge/GITHUB-KAVIKRUIZZ-003B00?style=for-the-badge&logo=github&logoColor=00FF41&labelColor=000000" alt="GitHub" /></a>
<a href="https://www.linkedin.com/in/kavikruizz"><img src="https://img.shields.io/badge/LINKEDIN-CONNECT-003B00?style=for-the-badge&logo=linkedin&logoColor=00FF41&labelColor=000000" alt="LinkedIn" /></a>


<br />

### `DECODE. DISRUPT. REWRITE.`

<sub><code>I wasn't coded to obey. I was born to rewrite the system.</code></sub>

<br /><br />

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00FF41,40:003B00,100:000000&height=100&section=footer" alt="Green matrix footer" width="100%" />

</div>
