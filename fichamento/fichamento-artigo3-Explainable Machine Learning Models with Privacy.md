# **Explainable Machine Learning Models with Privacy**

**Referência completa:**  
Bozorgpanah, Aso; Torra, Vicenç. *Explainable Machine Learning Models with Privacy*. In: *Progress in Artificial Intelligence*, vol. 13, pp. 31–50, 2024. Springer. doi: [10.1007/s13748-024-00315-2](https://doi.org/10.1007/s13748-024-00315-2)

---

## 1. Fichamento de Conteúdo

O artigo investiga a possibilidade de construir modelos de machine learning que sejam simultaneamente explicáveis e preservem a privacidade dos dados. Para isso, os autores avaliam o impacto de dois métodos de anonimização — microagregação (MDAV) e adição de ruído Laplaciano — sobre a qualidade das explicações geradas por meio do método TreeSHAP, uma variação do SHAP. São analisados três conjuntos de dados reais em experimentos comparativos com métricas como Irregularidade, Utilidade e Correlação de Rank. Os resultados mostram que o uso da técnica MDAV mantém, em grande parte, a utilidade do modelo e a interpretabilidade das decisões, enquanto a adição de ruído compromete mais severamente essas propriedades. Os autores concluem que é possível alcançar um equilíbrio razoável entre privacidade e explicabilidade, desde que o método de anonimização seja bem escolhido. A pesquisa contribui para o desenvolvimento de modelos de IA alinhados ao princípio de "privacidade por design", com implicações diretas em contextos regulatórios e éticos.

---

## 2. Fichamento Bibliográfico

- O artigo diferencia entre interpretabilidade (modelo compreensível por si só) e explicabilidade (capacidade de justificar decisões) (p. 32–34).  
- A abordagem utiliza o TreeSHAP para gerar explicações locais a partir de modelos treinados com dados mascarados (p. 34).  
- Microagregação com MDAV fornece k-anonimato e preserva melhor a estrutura explicativa do modelo original (p. 37–39).  
- A adição de ruído Laplaciano fornece privacidade diferencial local, mas prejudica significativamente a utilidade e a explicabilidade (p. 36–38).  
- A métrica de "Irregularidade" proposta mede distorções nas explicações após a aplicação de métodos de privacidade (p. 36).  
- A proteção por MDAV manteve alta correlação entre os atributos explicativos nos modelos originais e mascarados (p. 47).

---

## 3. Fichamento de Citações

- "We are interested in the process of developing data-driven models that, at the same time, make explainable decisions and are privacy-preserving." (p. 31)  
- "The effects of masking methods on XAI and, more concretely, on explainability are unknown." (p. 32)  
- "Our results show that some trade-off between privacy and explainability is possible for data protection using k-anonymity and noise addition." (p. 31)  
- "We develop a series of experiments comparing the effects of data masking procedures on the explainability of models according to SHAP." (p. 36)  
- "The MDAV method is the best-performing one. [...] Data had fewer irregularities, which preserve the utility (accuracy) of prediction." (p. 46)  
- "To sum up, we consider that explainable machine learning models can be considered along with privacy if data privacy methods preserve the three considered metrics." (p. 48)

