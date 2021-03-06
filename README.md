<div align="center">
    <a href="https://summerofcode.withgoogle.com/projects/#4822168754454528"><img src="https://i.imgur.com/JzXCPeO.png" width="550" alt="google-summer-of-code"></a>
    <br>
    <b> 
    <p>
    Adding support of Source Code Related Metrics to GrimoireLab for <a href="https://github.com/chaoss">CHAOSS</a> Project
    </p>
    </b>
</div>

<p align="center">
    <code> 
	<a href="#-project-abstract">Project Abstract</a>&nbsp;&nbsp;&nbsp;
    <a href="#-pull-requests--issues">Pull Requests & Issues</a>&nbsp;&nbsp;&nbsp;
    <a href="#-weekly-summary">Weekly Summary</a>&nbsp;&nbsp;&nbsp;
	<a href="#-would-like-to-sync">Would like to sync?</a>&nbsp;&nbsp;&nbsp;
    <a href="#-links">Links</a>
    </code>
</p>

<p align="center">
	<b> <sub>Check out my <a href="https://inishchith.github.io/blog"> <code>blog</code> </a> or follow me on <a href="https://twitter.com/inishchith"> <code>Twitter</code> </a> for weekly updates.</sub></b>
</p>
<br>

<br>

## # Project Abstract

+ Graal produces analysis related to code complexity, quality, dependencies, vulnerability and licensing and the data produced conforms to the ones that can be processed by GrimoireLab, however currently it is not integrated with GrimoireLab.

> <i> The aim of this project is to add Graal to the GrimoireLab toolchain in order to produce source code related Metrics </i>

<br>

## # Pull Requests & Issues

**#** **Repository: grimoirelab-graal** [**`/working-branches`**](https://github.com/inishchith/grimoirelab-graal/branches)

Pull requests created:
1. [chaoss/grimoirelab-graal#29](https://github.com/chaoss/grimoirelab-graal/pull/29): [colic] Add support of scancode_cli to colic backend **`/cp1`**
2. [chaoss/grimoirelab-graal#32](https://github.com/chaoss/grimoirelab-graal/pull/32): [graal] Derive `git_path` from `uri` **`/cp1`**
3. [chaoss/grimoirelab-graal#34](https://github.com/chaoss/grimoirelab-graal/pull/34): [logger] Switch `info` logger level to `debug` **`/cp1`**
4. [chaoss/grimoirelab-graal#37)](https://github.com/chaoss/grimoirelab-graal/pull/37): [analyzer] Fix results for deleted files for CoCom backend **`/cp1`**
5. [chaoss/grimoirelab-graal#38](https://github.com/chaoss/grimoirelab-graal/pull/38): [cocom] Add repository level analysis option for CoCom backend **`/cp1`**
6. [chaoss/grimoirelab-graal#39](https://github.com/chaoss/grimoirelab-graal/pull/39): [cocom] Add repository level analysis via lizard **`/cp1`**
7. [chaoss/grimoirelab-graal#40](https://github.com/chaoss/grimoirelab-graal/pull/40): [docs] Update documentation and links to requirements **`/cp2`**
8. [chaoss/grimoirelab-graal#41](https://github.com/chaoss/grimoirelab-graal/pull/41): [analyzer] Fix scancode_cli results **`/cp2`**
9. [chaoss/grimoirelab-graal#46](https://github.com/chaoss/grimoirelab-graal/pull/46): [cloc] Fix cloc error due to mulitple word language-name **`/cp2`**
10. [chaoss/grimoirelab-graal#50](https://github.com/chaoss/grimoirelab-graal/pull/50): [colic] Add copyright flag for extraction of copyright information **`/cp3`**


Issues opened:
1. [chaoss/grimoirelab-graal#18](https://github.com/chaoss/grimoirelab-graal/issues/18): [discussion] Improvements in existing analyzers and additions **`/ap`**
2. [chaoss/grimoirelab-graal#27](https://github.com/chaoss/grimoirelab-graal/issues/27): [colic] Add scancode_cli option to CoLic Backend **`/cp1`**
3. [chaoss/grimoirelab-graal#33](https://github.com/chaoss/grimoirelab-graal/issues/33): [graal] Checkout log an issue in case of large repositories **`/cp1`**
4. [chaoss/grimoirelab-graal#35](https://github.com/chaoss/grimoirelab-graal/issues/35): [analyzer] Fix results for deleted files **`/cp1`**
5. [chaoss/grimoirelab-graal#36](https://github.com/chaoss/grimoirelab-graal/issues/36): [cocom] Evaluating results with repository level analysis **`/cp1`**
6. [chaoss/grimoirelab-graal#47](https://github.com/chaoss/grimoirelab-graal/issues/47): [cocom] Redundant log on every file-open operation **`/cp2`**
7. [chaoss/grimoirelab-graal#48](https://github.com/chaoss/grimoirelab-graal/issues/48): [colic] Incorrect extraction of copyright information **`/cp3`**
8. [chaoss/grimoirelab-graal#49](https://github.com/chaoss/grimoirelab-graal/issues/49): [colic] Add copyright flag for extraction of copyright information **`/cp3`**
9. [chaoss/grimoirelab-graal#54](https://github.com/chaoss/grimoirelab-graal/issues/54): [colic] Slow execution of ScanCode-CLI **`/cp3`**
10. [chaoss/grimoirelab-graal#55](https://github.com/chaoss/grimoirelab-graal/issues/55): [colic] KeyError on execution of ELK with ScanCode-CLI **`/cp3`**
11. [chaoss/grimoirelab-graal#56](https://github.com/chaoss/grimoirelab-graal/issues/56): [cocom] Impossible to checkout the worktree **`/cp3`**


**#** **Repository: grimoirelab-elk** [**`/working-branches`**](https://github.com/inishchith/grimoirelab-elk/branches)

Pull requests created:
1. [chaoss/grimoirelab-elk#650](https://github.com/chaoss/grimoirelab-elk/pull/650): [elk] Add option to fetch from selected branches **`/cp2`**
2. [chaoss/grimoirelab-elk#651](https://github.com/chaoss/grimoirelab-elk/pull/651): [graal] Add support of Graal's CoCom Backend to ELK **`/cp2`**
3. [chaoss/grimoirelab-elk#653](https://github.com/chaoss/grimoirelab-elk/pull/653): [graal] Add support of Graal's CoLic Backend to ELK **`/cp2`**
4. [chaoss/grimoirelab-elk#664](https://github.com/chaoss/grimoirelab-elk/pull/664): [graal] Add support of Graal's CoCom Backend to ELK (study approach) **`/cp2`**
5. [chaoss/grimoirelab-elk#669](https://github.com/chaoss/grimoirelab-elk/pull/669): [graal] Add support of Graal's CoLic Backend to ELK (study approach) **`/cp2`**
6. [chaoss/grimoirelab-elk#672](https://github.com/chaoss/grimoirelab-elk/pull/672): [graal] Add support of Graal CoCom & CoLic Backend (finalized) **`/cp3`**


Issues opened:
1. [chaoss/grimoirelab-elk#642](https://github.com/chaoss/grimoirelab-elk/issues/642): Add option to fetch from selected branches **`/cp1`**


**#** **Repository: grimoirelab-tutorial** [**`/working-branches`**](https://github.com/inishchith/grimoirelab-tutorial/branches)

Pull requests created:
1. [chaoss/grimoirelab-tutorial#86](https://github.com/chaoss/grimoirelab-tutorial/pull/86): [graal] Add Graal to the Sidebar **`/cp1`**
2. [chaoss/grimoirelab-tutorial#87](https://github.com/chaoss/grimoirelab-tutorial/pull/87): [micro] Add tutorial for exectution of Micro-Mordred via Docker-Compose **`/cp1`**

Issues opened:
1. [chaoss/grimoirelab-tutorial#84](https://github.com/chaoss/grimoirelab-tutorial/issues/84): [components] How to play with Grimoirelab components **`/cp1`**

**#** **Repository: grimoirelab-sirmordred** [**`/working-branches`**](https://github.com/inishchith/grimoirelab-sirmordred/tree/graal_integration_config)

Pull requests created:
1. [chaoss/grimoirelab-sirmordred#320](https://github.com/chaoss/grimoirelab-sirmordred/pull/320): [graal] Add configuration for Graal integration in ELK **`/cp3`**


**#** **Repository: grimoirelab-sigils** [**`/working-branches`**](https://github.com/inishchith/grimoirelab-sigils/tree/graal_panels)

Pull requests created:
1. [chaoss/grimoirelab-sigils#380](https://github.com/chaoss/grimoirelab-sigils/pull/380): [graal] Add Code Complexity(CoCom) & Code License(CoLic) panels **`/cp3`**


**#** **Repository: metrics** **`/working-branches`**

Issues opened:
1. [chaoss/metrics#139](https://github.com/chaoss/metrics/issues/139): New Metrics: Support of source code related metrics **`/ap`**

> **Tags**:
>
> **a**pplication **p**eriod : **`/ap`** <br>
> **c**ommunity **b**onding period : **`/cb`** <br>
> **c**oding **p**eriod **x** - **`/cpx`** <br>


- **Do check issue tracker in current repository for some more info.**

<br>

## # Weekly Summary

### Community Bonding - May 6th to May 27th, 2019

+ [Accepted for GSoC 2019 & 1st Meeting](https://inishchith.github.io/blog/2019/05/introduction.html)
+ [A kick start meeting](https://inishchith.github.io/blog/2019/05/community-bonding-2.html)

### Coding Period 1 - May 28th to June 28th, 2019

+ Week #1: [Summary](./work/week1) | Blog Post: [[week-1] Learning how micro-mordred works..](https://inishchith.github.io/blog/2019/06/coding-period-1-1.html)
+ Week #2: [Summary](./work/week2) | Blog Post: [[week-2] Evaluating approaches and Initial integration of Graal](https://inishchith.github.io/blog/2019/06/coding-period-1-2.html)
+ Week #3: [Summary](./work/week3) | Blog Post: [[week-3] Ideate Visualize Repeat](https://inishchith.github.io/blog/2019/06/coding-period-1-3.html)
+ Week #4: [Summary](./work/week4) | Blog Post: [[week-4] Structuring data & Evaluating approaches](https://inishchith.github.io/blog/2019/06/coding-period-1-4.html)

### Coding Period 2 - June 28th to July 26th, 2019

+ Week #5: [Summary](./work/week5) | Blog Post: [[week-5] And.. we have our first dashboard](https://inishchith.github.io/blog/2019/06/coding-period-1-5.html)
+ Week #6: [Summary](./work/week6) | Blog Post: [[week-6] Much needed... Pace](https://inishchith.github.io/blog/2019/07/coding-period-2-6.html)
+ Week #7: [Summary](./work/week7) | Blog Post: [[week-7] Scope of improvement](https://inishchith.github.io/blog/2019/07/coding-period-2-7.html)
+ Week #8: [Summary](./work/week8) | Blog Post: [[week-8] Finalizing the Enrichment phase](https://inishchith.github.io/blog/2019/07/coding-period-2-8.html)

### Coding Period 3 - July 26th to August 19th, 2019

+ Week #9: [Summary](./work/week9) | Blog Post: [[week-9] The Final Coding Phase](https://inishchith.github.io/blog/2019/08/coding-period-3-9.html)
+ Week #10: [Summary](./week10/readme.md) | Blog Post: [[week-10] Regression testing & Evaluating results](https://inishchith.github.io/blog/2019/08/coding-period-3-10.html)

<br>

## # Would like to sync?

+ We have planned to keep all the communication open 🎉 so that everyone can sync and is free to participate and help us grow! So if you have suggestions / comments about anything please do not hesitate to open up an [issue ticket](https://github.com/inishchith/gsoc-graal/issues).
+ We will be discussing about the progress of this project every week at the **`#grimoirelab`** channel on FREENODE IRC (scheduled for every Friday 12:30 CEST or 16:00 IST). The transcripts of the meetings (chats) are available in **`/meetings`** directory.
+ There will be a weekly [blog post](https://inishchith.github.io/blog) as you might have noticed the weekly-summary log above which i'll make sure to also post on the [mailing lists](https://lists.linuxfoundation.org/mailman/listinfo/oss-health-metrics) of CHAOSS.

<br>

## # Links

+ GSoC project [proposal](./notes/gsoc-proposal-inishchith.pdf)
+ Graal: The Quest for Source Code Knowledge [paper](https://www.researchgate.net/publication/326942711_Graal_The_Quest_for_Source_Code_Knowledge)


<br>

### `Footnotes`

+ Work done during application period can be found here : [Contributions](./notes/application-period-contributions.md) & [Micro-tasks](https://github.com/inishchith/chaoss-microtasks)

