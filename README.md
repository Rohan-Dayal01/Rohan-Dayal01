Introduction
- 👋 Hi, I’m @Rohan-Dayal01. **Please read me** to get a sense of what I'm interested in and what work I am most proud of!
- 👀 I’m interested in data science, machine learning, and software engineering projects that with direct societal impact. 
- During the Summer of 2021, I worked as a Machine Learning Software Engineer Intern at NASA. There, I built natural language processing text classifiers to generate features which could be used to categorize research papers using Earth Science datasets (Code [here](https://git.earthdata.nasa.gov/projects/GDRMS/repos/ges-disc-reference-management-system/browse/paper_classification?at=summer2021) in public repo). I used the TF-IDF vectorization technique on the text abstracts, and then trained Multinomial Naïve Bayes and Random Forest algorithms. After training the models to serve as binary classifiers, I then created a pipeline which integrated my machine learning classifiers with the online publication management system. The pipeline, which is described in more detail in the repo, allows for one to pull new data through the API, classify it using the Multinomial Naïve Bayes algorithm, and then push the classification back to the citation management system.
Using this categorization, along with other features, my team of interns and I then created a graph database to link different research papers using Earth Science data, different datasets relating to those research papers, and other features. The goal of this was to make it easier for Earth Science researchers to find the data they need in order to tackle the critical climate research they are working on. We then created a web-application from which users could query the graph database. Here, we implemented hash query matching, and I developed a result ranking algorithm which took into account a result's popularity (number of times it was returned) as well as the degree of the result node. The web-application can be found in [this](https://git.earthdata.nasa.gov/projects/GDRMS/repos/ges-disc-reference-management-system/browse/searchWebApp/flaskr?at=summer2021) public repository.
- Both projects were officially published with the following publication DOIs: [10.6084/m9.figshare.15054192.v1](https://esip.figshare.com/articles/poster/Automated_classification_of_scientific_publications_linked_to_GES_DISC_datasets/15054192/1), [10.6084/m9.figshare.15054267.v1](https://esip.figshare.com/articles/poster/Creating_a_knowledge_graph_to_connect_scientific_publications_and_datasets_for_improving_discovery_of_GES_DISC_s_data_and_services/15054267/1)
- Other than the work I did at NASA, I have also worked on other socially impactful projects, such as the NLP Research I worked on last year to understand the impact of COVID-19 on the quality of healthcare for expectant women ([Notebook here](https://github.com/Rohan-Dayal01/COVIDNursingNLPAnalysis)). 

- 🌱 I’m currently learning about financial engineering through a Coursera course. I have been learning more about the financial markets over the past year due to the innumerable applications of data science and traditional software engineering across the sector.

- 💞️ Broadly, I'm looking to collaborate on any interesting projects that have direct societal impact, so feel free to reach out to me with any ideas or proposals! My specific skills are listed at the bottom of this file.

- 📫 How to reach me: You can email me at rohan.dayal@columbia.edu

My Programming Arsenal:
- Python, R: Years of experience with Machine Learning modeling and Data Science tools Scikit-Learn, TensorFlow, Keras, pandas, and NumPy. Extensive experience with Natural Language Processing specific libraries of NLTK, Gensim, and spaCy. Experience with Flask for building web-applications. Kaggle Certified: Intro to Deep Learning ; Intro to ML 
- Java, C: Software development, data structures, algorithms, linear algebra simulations, network programming.
- HTML, CSS, JavaScript: Experience using HTML, CSS, and JavaScript for building frontends of websites and web-applications.
- SQL, Gremlin: Integrating PostgreSQL with web apps. Building databases and query algos. for graph DBs with Gremlin.
- Linux/Unix: Bash/zsh terminal, shell scripting, process automation, and Git. Experience working with AWS, GCP.

<!---
Rohan-Dayal01/Rohan-Dayal01 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
