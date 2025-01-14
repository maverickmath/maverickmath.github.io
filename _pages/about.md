---
permalink: /
title: "Sobre mim"
excerpt: "Sobre mim"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
Olá! Sou Gladstone, **Engenheiro de Decisões**. 

Passo a maior parte do tempo pensando em como indivíduos e organizações tomam decisões, pequenas e grandes; em como elas *deveriam* tomar decisões; sobre o que as afastam desse ideal; e sobre o que perdemos com essa divergência. Tenho grande interesse pelos diferentes modos com que as pessoas pensam e refletem, absorvem, armazenam e recuperam informação, constroem, representam e comunicam conhecimento. A racionalidade, os processos cognitivos formais, seus vieses naturais, as formas de reduzir seus impactos sobre nossas vidas individuais e sobre o funcionamento de nossas instituições.

Engenharia de decisões
======
Nós tomamos decisões de acordo com o que entendemos das cadeias de relações causais que levam das nossas ações às suas consequências. Assim, podemos aumentar a qualidade de nossas decisões quando deixamos de lado a intuição e colocamos o processo decisório em si como objetivo de *design*. 

Mesmo grandes organizações podem tomar decisões ruins. Prever as consequências das decisões tomadas é uma tarefa não-trivial e não se resume a calcular o "impacto esperado sobre o lucro líquido no próximo trimestre". Com frequência, existem *múltiplos objetivos* a serem atendidos simultaneamente com uma decisão, muitos deles “intangíveis” (ou seja, difíceis mas não impossíveis de mensurar).

Encontrar um equilíbrio entre a complexidade do problema de decisão e a sofisticação das práticas decisórias a ela aplicadas é fundamental para gerar decisões de qualidade. É tarefa do “Engenheiro de Decisões” analisar cada situação de decisão e recomendar o conjunto de ferramentas adequadas ao seu tratamento. É seu objetivo incorporar técnicas avançadas de **Data Science**, **Pesquisa Operacional** e **Inteligência Computacional** ao conjunto de ferramentas de trabalho das pessoas responsáveis por tomar decisões em organizações grandes e pequenas, públicas e privadas.

Pela aplicação de princípios de engenharia é possível moldar o processo decisório de modo a incorporar todos os dados, conhecimento especialista e perspectivas relevantes ao contexto de uma decisão. Desse modo, pela aplicação de uma abordagem de Engenharia de Decisões é possível:

- melhorar a qualidade das decisões tomadas em sua organização;
- tomar decisões mais rápidas, consonantes com a rapidez do processo de desenvolvimento em si (*agile decision making*);
- reduzir os riscos associados às decisões tomadas;
- reutilizar ou modificar decisões anteriores à luz de novas informações e conhecimento (*decision template*).

Se você ficou interessado e deseja saber mais sobre as possibilidades oferecidas pelas técnicas de Análise de Decisões para sua organização ou mesmo para sua vida pessoal, entre em contato.

Produtividade pessoal
======
Sou apaixonado pela ideia de ajudar as pessoas a se tornarem mais produtivas, não apenas por meio da análise de decisões...

Tenho uma newsletter semanal...

Influências intelectuais
======
1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
1. Fork [this repository](https://github.com/academicpages/academicpages.github.io) by clicking the "fork" button in the top right. 
1. Go to the repository's settings (rightmost item in the tabs that start with "Code", should be below "Unwatch"). Rename the repository "[your GitHub username].github.io", which will also be your website's URL.
1. Set site-wide configuration and create content & metadata (see below -- also see [this set of diffs](http://archive.is/3TPas) showing what files were changed to set up [an example site](https://getorg-testacct.github.io) for a user with the username "getorg-testacct")
1. Upload any files (like PDFs, .zip files, etc.) to the files/ directory. They will appear at https://[your GitHub username].github.io/files/example.pdf.  
1. Check status by going to the repository settings, in the "GitHub pages" section

Prioridades
======
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

I have also created [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the academicpages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring academicpages can be found in [the guide](https://academicpages.github.io/markdown/). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
