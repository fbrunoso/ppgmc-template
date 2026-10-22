# Modelo LaTeX PPGMC/UESC — versão 2.0 (candidata)

**Versão 2.0 (2026):** Francisco Bruno Souza Oliveira.
**Baseada na versão 1.4:** Valdex de Jesus Santos (autor), com colaboração de Francisco Bruno Souza Oliveira.
A versão 1.4 original é preservada em `historico/`.

## Uso no Overleaf

1. Importe o ZIP do projeto.
2. Abra `configuracao.tex` e altere autor, título, orientação, banca, modalidade e etapa.
3. Escolha **pdfLaTeX** e **Biber** (bibliografia).
4. Compile `main.tex`.
5. Substitua os exemplos por conteúdo científico próprio.
6. Para ficha catalográfica oficial, coloque `pretextuais/ficha-catalografica.pdf` e descomente a linha `\includepdf` indicada em `main.tex`.

## Modos

- Mestrado / qualificação: relatório preliminar, banca de qualificação e cronograma.
- Doutorado / qualificação: idem, respeitando as particularidades regulamentares.
- Mestrado / defesa: dissertação e folha de aprovação.
- Doutorado / defesa: tese e folha de aprovação.

## Identidade visual e fonte

O logotipo do PPGMC foi fornecido pelo usuário. O arquivo original está em `figuras/logo-ppgmc-enviado.png`; a versão de tinta verde escura para fundo branco está em `figuras/logo-ppgmc-original-adaptado.png`, preservando o desenho. O brasão da UESC foi selecionado entre os arquivos PNG institucionais fornecidos pelo usuário. `newtxtext` e `newtxmath` fornecem tipografia Times-equivalente no texto e na matemática.

## Limitações

O estilo bibliográfico automatizado e as folhas de banca exigem homologação normativa e institucional antes de adoção oficial. A composição dos membros de defesa deve respeitar os quantitativos e a homologação do colegiado; coorientadores na qualificação são adicionais ao mínimo. Os exemplos científicos e as datas do cronograma são didáticos.
