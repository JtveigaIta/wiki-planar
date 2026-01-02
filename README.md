
#planar #utm #uas #bvlos #simulacao #resiliencia #safety #sms  
#sistemas-multiagentes #mas #ai #falhas #replanejamento  
#br-utm #icao #anac #decea #astm #doc10019  
#engenharia-de-sistemas #simulador #pesquisa-aplicada

---
## License
This project is licensed under the MIT License — see the LICENSE file for details.

## Visão Geral

O **PlaNAR (Planning and Resilient Architecture for UTM)** é um projeto de **pesquisa, desenvolvimento e documentação técnica** voltado à criação de um **simulador de Gerenciamento de Tráfego Aéreo Não Tripulado (UTM)**, com foco em:

- operações **BVLOS**,
- **resiliência operacional**,
- **gestão de falhas**,
- **replanejamento dinâmico de missões**,
- integração entre **drones autônomos, operadores, provedores UTM (USS) e autoridades**.

Esta Wiki constitui a **documentação oficial do projeto PlaNAR**, funcionando simultaneamente como:

- 📘 documentação técnica do simulador  
- 🧪 diário de bordo do desenvolvimento  
- 📚 biblioteca de modelos conceituais  
- 🎓 base oficial de cursos e minicursos  
- 📄 repositório de produção científica e técnica  

---

## Objetivos do Projeto

Os principais objetivos do PlaNAR são:

- Desenvolver um **ambiente de simulação UTM modular e extensível**
- Permitir a **avaliação de Safety, SMS, Resiliência e Falhas** em operações UAS
- Apoiar **pesquisa acadêmica, ensaios institucionais e capacitação técnica**
- Servir como base para **testes operacionais, análise regulatória e estudos prospectivos**
- Documentar decisões, hipóteses e aprendizados de forma **reprodutível e transparente**

---

## Escopo da Wiki

Esta Wiki cobre, de forma integrada:

- Fundamentos de **UTM e ATM aplicados a UAS**
- Normas nacionais e internacionais (**ICAO, ASTM, ANAC, DECEA**)
- Arquitetura do simulador PlaNAR
- Modelos conceituais (estilo ASA)
- Biblioteca de modelos e componentes
- Desenvolvimento de software e engenharia
- Experimentos, estudos de caso e ensaios
- Conteúdo didático e formação profissional

> **Nota:** A Wiki é um artefato vivo. Seu conteúdo evolui conforme o projeto avança.

---

## Estrutura da Documentação

A documentação está organizada em capítulos numerados para facilitar leitura progressiva:

1. **Início** — visão geral e links essenciais  
2. **Diário de Bordo** — decisões, hipóteses e aprendizados  
3. **Visão Geral do PlaNAR** — objetivos, escopo e roadmap  
4. **UTM e Base Normativa** — normas, CONOPS e regulamentação  
5. **Arquitetura do Simulador** — visão sistêmica e integração  
6. **Modelos Conceituais** — fundamentos da simulação  
7. **Biblioteca do Simulador** — componentes e APIs  
8. **Desenvolvimento e Engenharia** — práticas e padrões  
9. **Experimentos e Estudos de Caso** — validações e análises  
10. **Curso e Formação** — conteúdo didático e capacitação  
11. **Publicações e Eventos** — produção técnica e científica  
12. **Parcerias e Ecossistema** — colaborações institucionais  
13. **Como Contribuir** — participação e governança  

---

## Ecossistema PlaNAR

O PlaNAR é composto por três sistemas integrados:

| Sigla | Nome | Função |
|------|------|--------|
| **PlaNAR UTM** | Núcleo do Simulador | Infraestrutura central que integra operadores, drones, provedores UTM, conflitos e registros. |
| **MRCF** | Mission Replanning and Control Framework | Replanejamento tático, análise de rotas e adaptação dinâmica de missões. |
| **MIRF** | Módulo de Injeção e Recuperação de Falhas | Emulação de falhas e estratégias de recuperação para avaliação da resiliência. |

---

## Links Essenciais

### Código e Documentação
- 🌐 Wiki / GitHub Pages:  
  https://jtveigaita.github.io/planar/

- 💻 Repositório MRCF:  
  https://github.com/JtveigaIta/mrcf

### Produção Científica
- 📄 Artigo MRCF (TechRxiv):  
  https://www.techrxiv.org/doi/full/10.36227/techrxiv.176283639.98510048

- 📦 Zenodo (repositório):  
  https://doi.org/10.5281/zenodo.17538046

### Formação e Divulgação
- 🎧 Podcast Minicurso UTM:  
  https://open.spotify.com/show/1JZtT0xjPKblUvoDTa4eNA

- ▶️ Vídeo Minicurso (teste):  
  https://youtu.be/FUlvEIXYhcg

- 📝 Cadastro no Curso:  
  https://forms.gle/g8Mowf2w3gNkPYAJA

### Institucional e Eventos
- 🛰️ Ensaios BR-UTM (DECEA):  
  https://br-utm.decea.mil.br/

- 🎤 Congresso SIGE:  
  https://youtu.be/0R38LGyPSgI

- 🧪 Revisor ENCITA / ITAEx:  
  https://paic.ita.br/evento/encita-2025/

- 🤝 Parceria — Ganesha Aviação:  
  https://www.ganeshaaviacao.com.br

---

## Governança e Autoria

**Fundador e Pesquisador Responsável**  
**Jackson Tavares Veiga**

- Mestre em Ciências  
- Doutorando em Sistemas de Defesa e Aeroespaciais (ITA)  
- Pesquisador em UAS, Simulação, Sistemas Multiagentes, Defesa e ATM/UTM  

🔗 Currículo Lattes:  
https://lattes.cnpq.br/8939850014070884

---

## Observações Finais

O PlaNAR não é apenas um simulador, mas um **ambiente de experimentação científica e técnica**, concebido para apoiar:

- pesquisa acadêmica rigorosa,
- desenvolvimento tecnológico,
- formação profissional,
- tomada de decisão informada em UTM.

> **Use esta Wiki como manual, laboratório e registro histórico do projeto.**

---

## Nota de Direitos Autorais e Propriedade Intelectual

© **2026 — Jackson Tavares Veiga**
**Todos os direitos reservados.**

O projeto **PlaNAR (Planning and Resilient Architecture for UTM)**, bem como **todo o seu conteúdo associado**, incluindo, mas não se limitando a:

* códigos-fonte, scripts e bibliotecas;
* arquiteturas de software e sistemas;
* modelos conceituais, diagramas, figuras e ilustrações;
* textos técnicos, documentação, relatórios e artigos;
* materiais didáticos, cursos, apresentações e mídias;
* experimentos, metodologias, cenários de simulação e resultados;

são de **titularidade exclusiva de Jackson Tavares Veiga**, na condição de **fundador, autor e responsável intelectual** pelo projeto.

É **vedada a reprodução, distribuição, modificação, tradução, engenharia reversa, reutilização comercial ou não comercial**, total ou parcial, por qualquer meio ou forma, **sem autorização prévia e expressa do autor**, exceto nos casos explicitamente permitidos por lei (como citações acadêmicas devidamente referenciadas).

O uso do PlaNAR para fins de:

* pesquisa acadêmica,
* ensaios institucionais,
* capacitação,
* validações técnicas ou regulatórias,

**não implica cessão de direitos autorais ou de propriedade intelectual**, devendo sempre respeitar os termos definidos pelo autor e a legislação vigente.

As marcas, nomes, siglas e identidades associadas ao projeto **PlaNAR**, incluindo **PlaNAR UTM**, **MRCF** e **MIRF**, são protegidas e não podem ser utilizadas de forma independente ou associativa sem consentimento formal.

---

### Contato para Autorizações e Parcerias

Solicitações de uso, licenciamento, parcerias institucionais ou acadêmicas devem ser encaminhadas diretamente ao autor:

**Jackson Tavares Veiga**
Fundador do Projeto PlaNAR
Pesquisador em UTM, UAS, Simulação e Sistemas Resilientes
jackson.veiga@alumni.usp.br

## License
This project is licensed under the MIT License — see the LICENSE file for details.

---
