# Design System - Ekolav Estética Automotivo

Base extraída da logo real (fundo preto, "E" laranja, "ESTÉTICA KOLAV" em branco e "AUTOMOTIVO" em laranja, arquivo de 150 px) e das fotos do perfil (carros escuros, brilho, placa EKOLAV). Público: donos de carro em Lavras.

## Resumo do tom visual
- Preto profundo com laranja da marca: showroom, brilho e velocidade.
- Títulos em condensada itálica maiúscula (sensação de movimento), corpo limpo e legível.
- Cortes diagonais, reflexo de luz passando nas fotos e muito contraste.

## 1. Cores

| Token | Hex | Uso |
|---|---|---|
| --black-950 | #070708 | Fundo do hero, rodapé |
| --black-900 | #0E0E10 | Seção escura alternada |
| --black-800 | #17171A | Cards sobre fundo escuro |
| --black-700 | #222226 | Bordas e divisores no escuro |
| --orange-500 | #F0561D | Cor de ação: botão primário (texto preto) |
| --orange-400 | #FF7A3D | Destaque em texto e linhas sobre fundo escuro |
| --orange-600 | #C94412 | Hover do botão, destaque sobre fundo claro |
| --steel-300 | #B7BAC2 | Texto secundário em fundo escuro |
| --steel-100 | #E9EBEF | Texto principal em fundo escuro |
| --paper | #F4F2EF | Fundo claro |
| --ink | #121214 | Texto em fundo claro |
| --muted | #5A5C63 | Texto secundário em fundo claro |
| --wa-500 | #25D366 | EXCLUSIVO do botão flutuante de WhatsApp |

Contrastes: #E9EBEF sobre #070708 acima de 15:1; #B7BAC2 sobre #0E0E10 acima de 9:1; #121214 sobre #F0561D acima de 5:1; #5A5C63 sobre #F4F2EF acima de 6:1.

## 2. Tipografia (Google Fonts)
- Títulos: Barlow Condensed (800 itálico, maiúsculas).
- Corpo e botões: Barlow (400, 500, 600).

| Nível | Desktop | Mobile | Peso | Entrelinha | Espaçamento |
|---|---|---|---|---|---|
| H1 | 92px | 54px | 800 itálico | 0.92 | -0.01em |
| H2 | 56px | 40px | 800 itálico | 0.98 | 0 |
| H3 | 28px | 25px | 700 | 1.1 | 0.01em |
| Rótulo | 13px | 12px | 600 | 1.4 | 0.18em, maiúsculas |
| Corpo | 18px | 16px | 400 | 1.65 | 0 |
| Botão | 16px | 16px | 700 | 1 | 0.06em, maiúsculas |

## 3. Componentes
- **Botão primário:** fundo #F0561D, texto #070708, canto cortado na diagonal (clip-path), altura mínima 56px. Hover: sobe 2px e vai para #FF7A3D. Foco: contorno branco de 3px.
- **Botão secundário:** transparente com borda branca a 40%.
- **Card escuro:** #17171A, borda 1px #222226, canto superior direito cortado. Hover: linha laranja na base.
- **Foto:** reflexo de luz diagonal passando no hover e moldura de canto laranja.
- **Input:** altura 52px, raio 4px, borda #222226. Foco: borda #F0561D.

## 4. Estética
- Raios mínimos (4px); a personalidade vem dos cortes diagonais (clip-path de 14px).
- Sombras: brilho laranja suave só em botão (0 10px 30px rgba(240,86,29,.25)).
- Espaçamento: escala de 8px. Seções com 104px no desktop e 64px no mobile.
- Ornamentos: faixa rolante com texto, linhas diagonais finas e números grandes vazados.

## 5. Conversão
- Botão laranja "Agendar pelo WhatsApp" no topo, após os serviços, nos passos e no fim.
- Botão do catálogo (wa.me/c) nos serviços e no hero.
- Prova real: fotos de carros de clientes, nota 5,0 e avaliações com nome.
- Verde do WhatsApp só no botão flutuante.

## Tokens prontos (CSS)
```css
:root{
  --black-950:#070708; --black-900:#0E0E10; --black-800:#17171A; --black-700:#222226;
  --orange-500:#F0561D; --orange-400:#FF7A3D; --orange-600:#C94412;
  --steel-300:#B7BAC2; --steel-100:#E9EBEF;
  --paper:#F4F2EF; --ink:#121214; --muted:#5A5C63;
  --wa-500:#25D366; --alert-600:#B3492E;
  --font-display:'Barlow Condensed','Arial Narrow',sans-serif;
  --font-body:'Barlow',-apple-system,'Segoe UI',sans-serif;
}
```
