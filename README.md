# Espectro LAB · Validação

Questionário de validação da ideia **Espectro LAB** para terapeutas, professores e famílias, com um painel de métricas para a equipa.

> O terapeuta pede. O LAB constrói. Materiais à medida, sem dados das crianças.

## O que tem

- Questionário em 5 passos (cerca de 7 minutos) com perguntas comuns e perguntas próprias de cada perfil.
- Perguntas ilustradas com exemplos dos materiais que o LAB quer produzir.
- Funciona no telemóvel e sem internet depois da primeira visita (PWA). Sem ligação, a resposta fica guardada no telemóvel e é enviada quando a internet voltar.
- Painel de métricas só para a equipa, protegido por uma chave.

## Links por perfil

Acrescente o perfil ao fim do link para abrir o questionário já com a audiência escolhida:

- `…/#terapeuta`
- `…/#professor`
- `…/#familia`
- `…/#painel` abre o painel da equipa (pede a chave).

## Onde ficam as respostas

As respostas são enviadas para uma folha do Google Sheets da equipa, através de um script do Google Apps Script publicado como aplicação Web. O endereço desse script está em `index.html`, na constante `SHEETS_URL`.

A chave do painel **não** está neste repositório. Está apenas no script, no Google Drive da equipa.

## Ficheiros

| Ficheiro | O que é |
| --- | --- |
| `index.html` | A página inteira: questionário, painel, estilos e código |
| `manifest.webmanifest`, `sw.js` | Instalação como app e funcionamento offline |
| `icons/` | Ícones gerados a partir do símbolo da marca (o Arco) |

Sistema visual: Espectro LAB v2.1 (Bricolage Grotesque + Lexend, paleta atlântico, mangal, mel e barro).
