# Brazilian Immigrant Women in Germany: Descriptive Analysis and Data Visualization :brazil: :de:


Welcome to the data analysis project focused on Brazilian immigrant women in Germany. This project delves into the profiles, preferences, and services desired and offered by this unique demographic. In collaboration with Ligia Fascioni, a UX designer, I present a comprehensive examination based on a dataset derived from a survey conducted between 3/12/2024 and 12/12/2024.


### Purpose
The primary objective of this analysis is to delve into the preferences and requirements of Brazilian women in Germany concerning services. By categorizing and comparing the desired and offered services, our aim is to identify potential gaps and alignments. The ultimate goal is to assess the viability of creating a dedicated tool, such as an app or portal, that could facilitate the exchange of services among this community.


### Method for data retrieval
The dataset was curated through a meticulous reading and classification of responses to a 14-question survey distributed via Google Form. Responses were collected through LinkedIn posts, WhatsApp groups, and collaboration with relevant organizations.The questions are ilustrated in the end of this document.

### Approach
This analysis involves data cleaning, wrangling, and classification, with a particular focus on the challenges posed by open-ended responses. I utilized tools such as Google Sheets, Excel, and Python (Pandas in [Jupyter Notebook](https://github.com/KC2016/brazilian_immigrant_women_in_germany/blob/main/jupyter_notebook)) for efficient data manipulation and visualization.

The services were categorized into 19 [groups](https://github.com/KC2016/brazilian_immigrant_women_in_germany/blob/main/services_categories.txt), and the rates of desired categories were compared with those of the offered categories.

### Challenges
Classifying services proved to be a challenging task, given the variety of responses. I encountered instances of detailed stories and venting, requiring manual classification. Despite the challenges, the insights gained are valuable for understanding the nuances of service preferences.

### Tools used
- Google Sheets and Google Docs
- Excel
- Python, Pandas, Jupyter Notebook

Through a combination of these tools, I was able to streamline the analysis process and present our findings visually using Excel for data visualization and dashboards.

### Main outcomes

#### About the women
> As expected,  the majority of these women **relocated to be with their partners or spouses (51%)**, reflecting the significant role of familial ties in migration decisions.

>The majority of respondents **made the move to Germany within the past year**, indicating a recent influx of Brazilian women to the country.

> **Berlin (56%) stands out as the preferred city**, hosting the largest population of Brazilian women, followed by **Hamburg (15%)**.

> Unsurprisingly, language emerges as a significant barrier, with many respondents having **elementary or basic proficiency in German (A1,A2 and B1)**.

> Approximately 46% of them **had a previous residence in a country other than Germany**.

> Roughly 62% exclusively hold Brazilian citizenship and **do not possess European citizenship**.


#### About the services
> **Health and aesthetics** emerge as the top preferences among the **desired service categories**, while **jobs & business and social services** stand out as the most relevant in **the offerings**.

> Interestingly, we observed that there were significantly **more desired services (160) than offered services (66)**. The dataset revealed a **smaller volume of offered services**, which suggests that creating a platform solely for exchanging services among Brazilian women might face challenges due to the limited supply.

> **The most sought-after category is health**, which interestingly isn't prominently featured among the available services. However, **social services and aesthetics, both highly desired, are well-represented in the offerings**.

> It's notable that many women highlight a lack of certain attributes in the available services in Germany. **They express a need for services that are empathetic, connected, and kind (in Portuguese)**. Additionally, there is a strong demand for **high-quality, accessible online, child-friendly, extended-hour, personalized, and modern services**, indicating areas where the current offerings may fall short of meeting these preferences.

### About an app for services exchanges
Unfortunately, we did not identify a sufficient supply of services to meet the demand. So, a platform only for the exchange of service doesn’t seem that useful.

The data revealed a notable disparity, with 160 desired services compared to only 66 offered services. Additionally, some responses indicated unclear ideas about services to offer, such as ‘volunteering,’ or informal assistance services, like career coaching and support with language in bureaucratic tasks. This suggests that establishing a platform solely for exchanging services among Brazilian women may encounter obstacles due to the limited supply.

### Conclusions

This comprehensive analysis, grounded in a survey with 156 responses, highlights promising prospects for a dedicated tool facilitating service exchange among Brazilian women in Germany. Key considerations involve overcoming language barriers and tailoring services to match high-demand categories such as health and aesthetics. Incorporating unique attributes desired by the community is pivotal for the success of the platform.

While acknowledging the value of understanding demographic composition, including previous foreign residences, the focus shifts towards the observed disparity between desired and offered services. The analysis suggests that the careful alignment of services with community preferences is paramount, and strategies should be tailored to meet the specific needs of Brazilian women in Germany.

The service offering does not seem to be enough to move a specific app. So, we rethink the project guidelines to align with the needs of these women.

## Dashboards:

[![dashboard1](images/dashboard1_v2.png 'Dashboard1')](https://github.com/KC2016/brazilian_immigrant_women_in_germany/blob/main/images/dashboard1_v2.png)

[![dashboard2](images/dashboard2_v2.png 'Dashboard2')](https://github.com/KC2016/brazilian_immigrant_women_in_germany/blob/main/images/dashboard2_v2.png)

Explore more about these women and uncover insights into the services they desire and offer. Gain a deeper understanding of their stories and challenges.

## Note on Data Representativeness:

The insights presented in this article are derived from a survey conducted on a sample of 156 Brazilian women in Germany. It’s crucial to acknowledge that this sample, while offering valuable perspectives, may not be fully representative of the entire Brazilian female immigrant population in the country. The presence of biases is acknowledged, and these findings should not be construed as official statistics. Rather, they provide a glimpse into the experiences and preferences of a specific group within the broader community. For a comprehensive understanding, further research with a more diverse and extensive sample would be necessary.

## Empirical Analysis
In this [post in Medium](https://medium.com/@karina.condeixa/beyond-borders-unveiling-service-desires-of-brazilian-women-in-germany-feb8d691284b), I performed a detailed empirical analysis for a general public, covering a non-technical audience.

___
### Questions of the survey:

#### Qual o motivo de ter se mudado para a Alemanha?

- Trabalho
- Cônjuge/namorado(a)
- Família (pais, filhos)
- Busca de novas oportunidades
- Other

#### Há quantos anos você está na Alemanha?
- menos de 1 ano
- entre 1 e 5 anos
- entre 5 e 10 anos
- mais de 10 anos

#### Em qual cidade da Alemanha você está morando?

#### Você já tem cidadania europeia?
- tenho a alemã
- tenho de outro país da Europa
- não tenho cidadania europeia

#### Qual o seu nível de alemão?
- não fala e nem entende nada
- básico (frases simples)
- nível B1 (consegue se comunicar e resolver questões básicas)
- nível B2 (consegue se comunicar sem problemas e com desembaraço)
- nível C1 ou C2 (acadêmico)
- fluente

#### Você já morou fora do Brasil antes de vir para a Alemanha?
- Não
- Sim

#### Em qual país(es) você morou antes? Fale um pouco a respeito, se possível. Era melhor, pior, diferente em que sentido? Por que resolveu se mudar de lá?

#### Quais as dificuldades que você experimentou logo que mudou para a Alemanha? Escolha quantas respostas julgar adequadas.
- idioma
- moradia
- fazer amigos
- saúde/médicos
- transporte
- comida
- família
- integração
- burocracia
- clima
- roupas
- escola
- marido/esposa
- saudades de casa/- família/amigos
- animais
- carteira de motorista

#### Que tipo de serviço(s) você sente mais falta? Relate quantos achar necessários.

#### Você gostaria de oferecer algum tipo de serviço específico para brasileiras? Qual? Cite quantos julgar necessários.

#### Você conhece alguma dessas comunidades/grupos/serviços voltados para imigrantes brasileiras na Alemanha?
- Carlotas Mulheres Deutschland
- As Janaínas
- Mulheres do Brasil
- Brempex
- Brazilian Business Women in Berlin
- Profissionais de TI em Berlim (Mulheres)
- Brasileiras na Alemanha
- Encontro de Mulheres da Língua Portuguesa
- Ramifica
- Outra

#### Você acredita que se existisse algum tipo de portal ou aplicativo que conectasse a comunidade brasileira para divulgação de produtos/serviços/projetos VOLTADOS PARA MULHERES ajudaria na sua vida aqui na Alemanha de alguma forma? Por quê?

#### Fique à vontade para fazer sugestões e comentários adicionais! Pode ser um desabafo, algo sobre seus sentimentos, o que você quiser!