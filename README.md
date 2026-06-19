# AIMED OS · Residentes GO · 2ª Edição · Junho 2026

Plataforma permanente do curso AIMED Residentes GO — 2ª edição. Primeiro curso brasileiro de Inteligência Artificial aplicada à Ginecologia e Obstetrícia construído com metodologia autoral.

**Joinville · 26 e 27 de Junho de 2026 · 14h presenciais**

---

## Sobre

AIMED OS é o portal-livro-ferramenta que acompanha o curso e permanece disponível para as participantes sem data de expiração. É um único arquivo HTML, sem dependências externas, projetado para funcionar offline e por muitos anos.

- Metodologia AIMED — anatomia do prompt médico em 5 componentes (Assistente · Informações · Missão · Estrutura · Diretrizes)
- Teoria do Contrário (TdC) — exercício distribuído de defesa intelectual de protocolos
- Biblioteca de prompts especialistas em GO por nível N1→N2→N3
- Casos clínicos nomeados da turma (Bianca · Rafaela · Luciana)
- Fluxo orquestrado: Gemini → Claude → GPT
- NotebookLM GO/MDV
- Resolução CFM 2.454/2026 integrada ao módulo de ética

## Tecnologia

- HTML/CSS/JavaScript puro (sem build, sem dependências)
- ~360 KB, arquivo único
- Hospedagem: GitHub Pages
- Compatível com qualquer browser moderno · responsivo mobile
- PWA: instalável na tela inicial (iOS e Android)

## Estrutura pedagógica

| Bloco | Papel | Quando |
|---|---|---|
| 1 | Arquiteto | Sexta 16:00–18:00 |
| 2 | Clínico GO | Sexta 18:15–21:00 |
| 3 | Pesquisador | Sábado 08:00–12:00 |
| 4 | Integrador | Sábado 13:30–18:30 |
| 5 | Crescimento | Pós-curso · 4 semanas |

## Como rodar localmente

```bash
git clone https://github.com/mbulabarros/aimed-residentes-go-jun2026.git
cd aimed-residentes-go-jun2026
python3 -m http.server 8000
# abra http://localhost:8000
```

## Assets necessários

O arquivo HTML referencia os ícones PWA da pasta `icons/`. Copie a pasta `icons/` do repo [aimed-residentes-go](https://github.com/mbulabarros/aimed-residentes-go) — os ícones são idênticos entre as edições.

## Certificados

Validação via repo [certificados](https://github.com/mbulabarros/certificados) · `editions/2026-06_aimed_residentes_go.json`

## Autor

Dr. Mbula Luzingu Barros · InovaMed · inovamed.pro · inovamed.pro@gmail.com

---

*"Vamos para vencer e mudar a medicina do Brasil."*
