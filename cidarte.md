---
layout: post
title: Cidarte
---

## Modern Android Development

O **Cidarte** é um projeto desenvolvido para demonstrar o estado da arte no desenvolvimento Android nativo em 2025. É um aplicativo de descoberta de filmes que consome a API do TMDb, focado em **UI Declarativa**, **Animações Complexas** e **Arquitetura Escalável**.

### Destaques Técnicos
* **Interface 100% Compose:** UI construída inteiramente com Jetpack Compose e Material 3.
* **Animações Avançadas:** Implementação de *Flip Card 3D* (Cine Roleta) utilizando `graphicsLayer` e `animateFloatAsState`.
* **Performance:** Otimização de busca com operadores `Flow` (debounce, distinctUntilChanged) para reduzir chamadas de rede.
* **Arquitetura:** Clean Architecture + MVVM rigoroso.
* **Offline-First:** Cache local de dados utilizando Room Database.

### Tech Stack
* **Linguagem:** Kotlin
* **Injeção de Dependência:** Hilt
* **Assincronismo:** Coroutines & Flow
* **Rede:** Retrofit & OkHttp (com Interceptors)
* **Imagens:** Coil

## Demonstração

Veja o aplicativo em funcionamento:

<div style="display: flex; justify-content: center; margin: 20px 0;">
  <div style="position: relative; width: 100%; max-width: 315px; aspect-ratio: 9/16; border-radius: 12px; overflow: hidden; box-shadow: 0 4px 12px rgba(0,0,0,0.15);">
    <iframe 
      src="https://www.youtube.com/embed/vjfxVff1M9E" 
      style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;" 
      frameborder="0" 
      allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
      allowfullscreen>
    </iframe>
  </div>
</div>

## Links

* **[Ver código no GitHub](https://github.com/vinicalgaro/cidarte)**

---