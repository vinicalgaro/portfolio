---
layout: post
title: Guitar Notebook
---

## Sobre o Projeto

O **Guitar Notebook** é uma ferramenta completa para músicos organizarem seus estudos. Ele permite cadastrar nome, instrumento, afinação e links de referência, estruturando cada música em partes (verso, refrão) com sequências de acordes e padrões rítmicos detalhados.

O grande diferencial é o **Modo de Prática Interativo**: um player automático que rola a tela e exibe os diagramas de acordes e ritmos no tempo certo, permitindo que o músico se concentre apenas em tocar.

### Tecnologias e Arquitetura
* **Stack:** Flutter & Dart (Mobile e Web).
* **Arquitetura:** MVVM com Clean Architecture.
* **Gerência de Estado:** Provider e ChangeNotifiers.
* **Persistência:** Drift (SQLite no Android, IndexedDB na Web).
* **Engenharia:** CI/CD com GitHub Actions, Internacionalização (i18n) e Design System responsivo.

## Demonstração

Veja o aplicativo em funcionamento:

<div style="display: flex; justify-content: center; margin: 20px 0;">
  <div style="position: relative; width: 100%; max-width: 315px; aspect-ratio: 9/16; border-radius: 12px; overflow: hidden; box-shadow: 0 4px 12px rgba(0,0,0,0.15);">
    <iframe 
      src="https://www.youtube.com/embed/UPpffsrn4GA" 
      style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;" 
      frameborder="0" 
      allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
      allowfullscreen>
    </iframe>
  </div>
</div>

## Links

* **[Ver código no GitHub](https://github.com/vinicalgaro/Guitar-Notebook)**
* **[Acessar Versão Web](https://vinicalgaro.github.io/Guitar-Notebook/)**
* **[Baixar na PlayStore](https://play.google.com/store/apps/details?id=com.vinicalgaro.guitarnotebook)**

---