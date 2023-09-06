**Kaggle link**: https://www.kaggle.com/competitions/ml-olympiad-for-students-topvistos-eua/overview

### **Context**
Business communities in the United States face a high demand for human resources, but one of the constant challenges is identifying and attracting the right talent, which is perhaps the most important element in staying competitive. Companies in the United States are looking for hardworking, talented and qualified individuals both locally and abroad.

The US Immigration and Nationality Act (INA) allows foreign workers to come and work in the United States temporarily or permanently. The law also protects US workers from adverse impacts on their wages or working conditions by ensuring that US employers comply with legal requirements when hiring foreign workers to fill labor shortages. Immigration programs are administered by the Office of Foreign Employment Certification (OFLC).

The OFLC processes employment certification applications for employers seeking to bring foreign workers to the United States and grants certifications in cases where employers can demonstrate that there are not enough US workers available to perform the job at wages that meet or exceed the wage paid. for occupation in the intended field of employment.

### **Goal**
In fiscal 2016, OFLC processed 775,979 employer applications for 1,699,957 temporary and permanent labor certification positions. This represented a nine percent increase in the total number of orders processed over the previous year. The process of reviewing each case is becoming a tedious task as the number of applicants increases each year.

The increase in the number of applicants each year demands a solution based on Machine Learning that can help in the pre-selection of candidates with the highest chances of VISA approval. OFLC engaged his company, TopVistos, for data-driven solutions. As a Data Scientist, you must analyze the given data and, with the help of a classification model:

Facilitate the visa approval process.

Recommend a suitable profile for applicants for whom a visa is to be certified or denied, based on factors that significantly influence the status of the case.

### **Data Description**

**The dataset is in potuguese**. The data contains different employee and employer attributes. The detailed data dictionary is provided below.

#### Files
- **train.csv** - training dataset
- **test.csv** - test dataset

#### Data Dictionary

- **id_do_caso:** ID of each visa application
- **continente:** Employee continent information
- **educação_do_empregado:** Employee education information
- **tem_experiência_de_trabalho:** Does the employee have any work experience? S = Yes; N = No
- **requer_treinamento_de_trabalho:** Does the employee require any job training? S = Yes; N = No
- **num_de_empregados:** Number of employees in the employer's company
- **ano_de_estabelecimento:** Year in which the employer's company was established
- **região_de_emprego:** Information on the region of employment intended by the foreign worker in the US.
- **salário_prevalecente:** Average salary paid to workers in similar occupations in the intended employment area. The purpose of the prevailing wage is to ensure that the foreign worker is not underpaid compared to other workers who provide the same or similar service in the same field of employment.
- **unidade_de_salário:** Prevailing salary unit. Values ​​include Hourly, Weekly, Monthly, and Yearly.
- **posição_em_tempo_integral:** Is the work position full time? S = Full-Time Position; N = Part-Time Position
- **status_do_caso:** Indicator if the visa was certified or denied