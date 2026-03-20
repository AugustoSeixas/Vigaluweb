# VIGALU Web

**Cálculo de Vigas Contínuas de Concreto Armado — NBR 6118:2014**

Versão web do programa **VIGALU**, desenvolvido originalmente nos anos 1990 pelo Prof. Dr. Roberto Chust Carvalho e equipe no Departamento de Engenharia Civil (DECiv) da Universidade Federal de São Carlos (UFSCar).

🔗 **[Acesse aqui](https://SEU-USUARIO.github.io/vigalu-web/)** ← *(atualize com sua URL após publicação)*

---

## Sobre

O VIGALU original era um executável MS-DOS escrito em Microsoft QuickBASIC, utilizado como ferramenta didática para cálculo e dimensionamento de vigas contínuas de concreto armado. Fazia parte do ecossistema de softwares educacionais do grupo de pesquisa [CALCO](https://www.deciv.ufscar.br/calco/) da UFSCar.

Esta versão web é uma **homenagem funcional** ao programa original, reimplementada em HTML/CSS/JavaScript puro para funcionar em qualquer navegador moderno, sem necessidade de instalação.

## Funcionalidades

### Entrada de dados
- Vigas contínuas com até 8 vãos
- Cargas distribuídas (kN/m) e concentradas (kN) por vão
- Parâmetros da seção: fck, bw, h, d', coeficiente γf

### Análise estrutural
- Resolução pelo método de Clapeyron (Equação dos Três Momentos)
- Sistema tridiagonal resolvido pelo algoritmo de Thomas
- Diagrama de momentos fletores
- Tabela de reações de apoio
- Esforços críticos (M+, M−, V) por vão

### Dimensionamento — NBR 6118:2014
- **Flexão:** cálculo de armadura longitudinal (As), posição da linha neutra (x/d), verificação de domínio de deformação, armadura mínima
- **Cortante (Modelo I):** verificação da biela comprimida (Vrd2), cálculo de Vc e Vsw, taxa de estribos (Asw/s), espaçamento para ø5.0, ø6.3 e ø8.0 mm
- Aço CA-50 (fyk = 500 MPa)
- Coeficientes de segurança: γc = 1,4 · γs = 1,15

## Como usar

**Opção 1 — Online:** acesse a URL do GitHub Pages (link acima).

**Opção 2 — Local:** baixe o arquivo `index.html` e abra no navegador com duplo clique. Funciona offline.

Não há dependências, servidores ou instalação. É um único arquivo HTML autocontido.

## Créditos

### Programa original (c. 1990)
- **Prof. Dr. Roberto Chust Carvalho** — UFSCar / DECiv
- **Paulo Garcia** — UFSCar / DECiv
- **Fernando P. Santos** — UFSCar / DECiv
- **Marcos A. F. Silva** — UFSCar / DECiv

O programa original faz parte da tradição de ferramentas educacionais do grupo [CALCO — Cálculo de Concreto Armado](https://www.deciv.ufscar.br/calco/) do DECiv/UFSCar.

### Versão web (2026)
Reimplementação por Augusto Seixas, com auxílio de inteligência artificial (Claude/Anthropic), como homenagem ao programa original e contribuição ao ensino de engenharia estrutural.

## Aviso

**Ferramenta didática.** Destinada ao ensino e verificações rápidas. Não substitui o cálculo estrutural por profissional habilitado conforme a legislação vigente (Lei 5.194/66, Resolução CONFEA 1.048/2013).

## Licença

Este projeto é distribuído sob a licença [MIT](LICENSE).

O nome VIGALU e os créditos aos autores originais são preservados em respeito à obra intelectual que inspirou esta reimplementação.
