![logo](graficos/analise.jpeg)

## Análise comparativa dos indicadores socioeconômicos dos estados brasileiros  🚀 🚀 🚀 🚀

---

### Objetivos

---

* **Objetivo Geral:**
  * Identificar padrões, tendências e disparidades entre os estados brasileiros com base nos indicadores apresentados, buscando compreender as relações entre esses indicadores e as possíveis causas dessas diferenças.

---

### Perguntas

---

1. **Quais são os estados com as maiores e menores populações?**

![Gráfico de Barras vertical](graficos/img1.png)

O gráfico destaca as disparidades populacionais entre os estados do Brasil, mostrando que São Paulo possui a maior população, enquanto Roraima é o estado menos populoso. Essas informações podem ser úteis para discutir questões relacionadas à infraestrutura, economia e serviços públicos, além de suas implicações para políticas sociais e econômicas em diferentes regiões do país

---

2. **Como a renda per capita varia entre os estados?**

![Gráfico de Barras Horizontais](graficos/img2.png)

O gráfico ilustra a distribuição da renda per capita entre os estados, destacando as disparidades existentes. Ele mostra que estados como São Paulo e Distrito Federal têm as rendas per capita mais elevadas, enquanto estados como Acre e Maranhão apresentam as rendas mais baixas. Essas diferenças podem ser atribuídas a fatores como desenvolvimento econômico, acesso a empregos, educação e infraestrutura.

---

3. **Existe uma correlação entre a área territorial dos estados e seus indicadores socioeconômicos?**

![Gráfico de Dispersão](graficos/img3.png)

Tendência Geral: O gráfico mostrar se existe uma tendência de que estados com maiores áreas territoriais também tenham populações maiores. Isso pode indicar uma correlação positiva entre a extensão territorial e o número de habitantes.

Outliers: Estados como São Paulo, que têm uma população elevada em relação à sua área, podem se destacar como outliers, desafiando a ideia de que mais área sempre significa mais população.

Implicações Socioeconômicas: As diferenças populacionais em relação à área territorial podem refletir disparidades em infraestrutura, serviços públicos e desenvolvimento econômico, sugerindo que a densidade populacional e a distribuição territorial precisam ser consideradas nas políticas sociais e econômicas.

---

4. **Quais são os estados com as maiores disparidades na matrícula no ensino fundamental?**

![Gráfico de Boxplot (Diagrama de Caixa)](graficos/img4.png)

Esse gráfico fornece uma representação visual clara das matrículas no ensino fundamental por estado, permitindo análises sobre desigualdade educacional, impacto das políticas públicas e a relação entre condições socioeconômicas e acesso à educação.

---

5. **Como o Índice de Desenvolvimento Humano (IDH) se relaciona com outros indicadores socioeconômicos?**

![Gráfico de Mapa de Calor (Heatmap)](graficos/img5.png)

O gráfico de mapa de calor destaca como o Índice de Desenvolvimento Humano (IDH) se relaciona com outros indicadores socioeconômicos, revelando correlações importantes que podem informar políticas públicas e estratégias de desenvolvimento. Essas relações ajudam a compreender a complexidade do desenvolvimento humano e a importância de abordar diversas dimensões, como renda, educação e infraestrutura, para promover melhorias significativas na qualidade de vida da população.

---

6. **A renda per capita varia significativamente entre os estados brasileiros com IDH acima da média e aqueles com IDH abaixo ou igual à média?**

Pergunta da Hipótese:
Hipótese Nula (𝐻0): Não há diferença significativa na renda per capita entre os estados com IDH acima da média e os estados com IDH abaixo ou igual à média.

Hipótese Alternativa (𝐻1): Há uma diferença significativa na renda per capita entre os estados com IDH acima da média e os estados com IDH abaixo ou igual à média.


![# Gráfico de Boxplot Comparativo](graficos/img6.png)


---

### Bases de Dados

---

* **Fontes :**
  * Coleta de dados do IBGE por meio de web scraping permitiu construir um dataset abrangente sobre os indicadores sociais e econômicos dos estados brasileiros.

**link**

**AC** - <https://www.ibge.gov.br/cidades-e-estados/ac.html>
**AL** - <https://www.ibge.gov.br/cidades-e-estados/al.html>
**AP** - <https://www.ibge.gov.br/cidades-e-estados/ap.html>
**AM** - <https://www.ibge.gov.br/cidades-e-estados/am.html>
**BA** - <https://www.ibge.gov.br/cidades-e-estados/ba.html>
**CE** - <https://www.ibge.gov.br/cidades-e-estados/ce.html>
**DF** - <https://www.ibge.gov.br/cidades-e-estados/df.html>
**ES** - <https://www.ibge.gov.br/cidades-e-estados/es.html>
**GO** - <https://www.ibge.gov.br/cidades-e-estados/go.html>
**MA** - <https://www.ibge.gov.br/cidades-e-estados/ma.html>
**MT** - <https://www.ibge.gov.br/cidades-e-estados/mt.html>
**MS** - <https://www.ibge.gov.br/cidades-e-estados/ms.html>
**MG** - <https://www.ibge.gov.br/cidades-e-estados/mg.html>
**PA** - <https://www.ibge.gov.br/cidades-e-estados/pa.html>
**PB** - <https://www.ibge.gov.br/cidades-e-estados/pb.html>
**PR** - <https://www.ibge.gov.br/cidades-e-estados/pr.html>
**PE** - <https://www.ibge.gov.br/cidades-e-estados/pe.html>
**PI** - <https://www.ibge.gov.br/cidades-e-estados/pi.html>
**RR** - <https://www.ibge.gov.br/cidades-e-estados/rr.html>
**RO** - <https://www.ibge.gov.br/cidades-e-estados/ro.html>
**RJ** - <https://www.ibge.gov.br/cidades-e-estados/rj.html>
**RN** - <https://www.ibge.gov.br/cidades-e-estados/rn.html>
**RS** - <https://www.ibge.gov.br/cidades-e-estados/rs.html>
**SC** - <https://www.ibge.gov.br/cidades-e-estados/sc.html>
**SP** - <https://www.ibge.gov.br/cidades-e-estados/sp.html>
**SE** - <https://www.ibge.gov.br/cidades-e-estados/se.html>
**TO** - <https://www.ibge.gov.br/cidades-e-estados/to.html>

---

### Ferramentas Utilizadas

---

* **Linguagem de Programação:** Python
* **Bibliotecas:** Pandas, NumPy, Seaborn, Matplotlib, BeautifulSoup, Scipy
* **Ambiente de Desenvolvimento:** Jupyter Notebook e Visual Studio Code