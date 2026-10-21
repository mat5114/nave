# NAVE — proposta de site

Proposta de site para a **NAVE · Food & Drinks**, Rua de Santos Pousada 140, Porto ([@nave.porto](https://www.instagram.com/nave.porto/)).

A identidade parte do Instagram. O logo pixelado foi redesenhado numa grelha de 4×5 e serve de alfabeto para os títulos. A programação usa mono itálico, como nos cartazes mensais, e os destaques usam o marcador verde dos posts de texto. O site segue o tema claro ou escuro do dispositivo.

## Páginas

- **Início** (`#inicio`): manifesto, próximos eventos, menu, espaço, horário e localização.
- **Agenda** (`#agenda`): calendário mensal e vista em lista, filtros por tipo e o detalhe de cada evento. O detalhe abre por link direto, por exemplo `#ev-1024-valerio1900`.

## Estrutura

```
index.html   página única (HTML, CSS e JS sem dependências; fontes do Google Fonts)
img/         fotos e cartazes otimizados, mais a marca "Never Not Eating" extraída
```

Para ver localmente, sirva a pasta por HTTP, por exemplo com `python3 -m http.server`. A marca manuscrita usa `mask-image`, que não carrega via `file://`.

## Conteúdo a confirmar

- As datas dos eventos são **ilustrativas**. Os artistas e as séries vêm dos cartazes de março e abril de 2026. Para atualizar, edite o array `RAW` em `index.html`.
- O domingo aparece como encerrado, porque a bio só lista segunda a sábado.
- O menu descreve o que aparece nas fotos e não tem preços.
