# Análise Exploratória de Dados - Student Performance
Exploratory Data Analysis (EDA) sobre o desempenho de estudantes em matemática, leitura e escrita, usando Python (Pandas, Matplotlib, Seaborn).

Fonte do Dataset: [Kaggle](https://www.kaggle.com/datasets/spscientist/students-performance-in-exams)

---


### **Objetivos da Análise**
- Entender distribuição das notas
- Avaliar impacto de gênero e preparação no desempenho
- Identificar correlação entre matérias
- Resumo estatístico da análise

---

### **Tecnologias Utilizadas**
- Python 3
- Pandas
- NumPy
- Matplotlib / Seaborn

---

### **Principais Análises e Gráficos**
- Histogramas de notas
- Boxplots e barplots por gênero e preparação
- Heatmap de correlação
- Dispersão entre variáveis

---

### **Resumo de Insights**
- Meninas se destacam em leitura e escrita, meninos em matemática
- Preparação antes do teste melhora o desempenho geral
- Forte correlação entre leitura e escrita (0.95)

<br/>

# **Análises Detalhadas**
### Histograma
As 3 matérias tem medianas aproximadas, entre 65-70, o que indica que não há matéria discrepante no desempenho médio. E a distribuição entre Reading e Writing é bem parecida, o que sugere que algumas estratégias pedagogas podem impactar positivamente na escrita. 

<img width="1605" height="488" alt="Captura de tela 2025-10-04 020444" src="https://github.com/user-attachments/assets/64b621e8-5042-493d-b022-7bd2387bb549" />

### Análise Univariada Categórica
Meninas são predominantes e que apenas uma 35% dos alunos fizeram o teste preparatório (355/1000).

### Heatmap de Correlação
- Correlação forte positiva entre **Writing e Reading** (0.95).  
- Boa correlação entre **Math e Reading** (0.82), indicando dependência entre habilidades.

<img width="619" height="462" alt="Captura de tela 2025-10-04 020515" src="https://github.com/user-attachments/assets/99bbf77e-f99c-4dff-bd54-9e91bd08a4a0" />

### Gráfico de Dispersão
O gráfico mostra que quem vai mal em uma disciplina, tende a ir mal em outra.  
- Meninos tiveram desempenho melhor em matemática, mas pior em leitura.  
- Meninas tiveram desempenho melhor em leitura, mas um pouco inferior em matemática.

### Boxplot e Barplot (por gênero)
Os gráficos revelaram que as meninas tem uma nota inferior a dos meninos em matemática, mas em writing e Reading as meninas tem uma nota maior. Apesar disso, a maior parte dos outliers estão relacionados as garotas, sendo 2 ou 3 dos meninos em cada matéria.

<img width="1715" height="558" alt="Captura de tela 2025-10-04 020606" src="https://github.com/user-attachments/assets/89a76056-1b86-4df8-858a-ed0416519130" />


### Boxplot e Barplot (Teste Preparation)
Os gráficos comprovam que as maiores notas em todas as matérias **vem de alunos com preparação antes do teste**, sendo os gráficos de todas as matérias muito similares. Em relação aos Outliers, muitos deles estão concentrados nos que não tem o preparamento, apesar de ainda existir 2 ou 3 nos que tem preparação completa. Vale comentar que em Reading a quem tem preparação, não temos nenhum outliers.

<img width="1712" height="559" alt="Captura de tela 2025-10-04 020552" src="https://github.com/user-attachments/assets/feec128c-d6d1-482d-83b8-e453d9a3cc54" />

---

### Conclusão Final
A análise que realizei mostrou que o desempenho dos alunos apresentam alguns padrões claros:

-	**Diferenças de gênero**: Meninas têm desempenho superior em leitura e escrita, meninos em matemática.
-	**Preparação antes do teste** tem impacto positivo em todas as matérias, reduzindo inclusive a ocorrência de outliers em leitura.
-	**Correlação entre matérias** sugere que melhorias em literatura pode refletir em escrita, e vice-versa


---

### **Como Rodar o Projeto**
<code>git clone https://github.com/EllenNewerkla/EDA_Students_Performance.git 
cd EDA_Students_Performance/notebooks
jupyter notebook </code>
<br /> 


### **Vamos mater Contato!**
- [LinkedIn](https://www.linkedin.com/in/ellennewerkla/) <br/>
- [Email](mailto:ellennewerkla@gmail.com) <br/>
