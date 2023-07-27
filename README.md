# apache-superset
**This is a apache superset project**
The project will includes;
*Installation of the superset
*Creation of charts and dashbaords
*Advantages of superset over other alternatives (Tableau, Power Bi & Looker studion)

**Installation of the superset**
There are various installations set-up to chose from:
*Installing Superset Locally Using Docker Compose
*Installing Superset from Scratch
*Installing on Kubernetes
Link with all set-up steps: https://superset.apache.org/docs/installation/installing-superset-using-docker-compose

**Installing Superset Locally Using Docker Compose**

**Step 1: Install Docker Desktop for windows:**
Download using this link: https://www.docker.com/products/docker-desktop/

**Step 2: Apache superset installation using docker-compose:**
https://superset.apache.org/docs/installation/installing-superset-using-docker-compose/

step 2.1: git clone https://github.com/apache/superset
Step 2.2: cd incubator-superset
Step 2.3: docker-compose up

wait around 10 to 20 mins to setup everything

**Step3: Once above setup completes, open http://localhost:8088 in the browser**
username: admin
password: admin

Installation is complete, enjoy building dashboards using apache-superset

Important Youtube Vidoes (I don't own the channels)
https://www.youtube.com/watch?v=idCgc1tR1d0

*******************************************************************
**Creation of charts and dashbaords**
The Dashbaord was created using the raw data from Kaggle
The Raw data, 
The data was import to postgreSQL Database
Visua
*******************************************************************
**Advantages of superset over other alternatives (Tableau, Power Bi & Looker studion)**
Apache Superset, an open-source data visualization and business intelligence web application, has gained popularity due to its user-friendly interface and extensive features. Here are the pros and cons of Apache Superset:

**Pros:**
**Ease of Use:** Superset offers a simple and intuitive user interface, making it easy for both technical and non-technical users to create visualizations and dashboards without extensive coding knowledge.

**Data Source Variety:** It supports various data sources, including popular databases like MySQL, PostgreSQL, and many others, as well as big data platforms like Apache Hive and Presto.

**Rich Visualization Options:** Superset provides a wide range of visualization types and customization options, allowing users to build insightful and interactive dashboards.

**Security and Access Control:** It offers robust security features, including authentication, role-based access control, and integration with external authentication providers.

**Scalability:** Superset is designed to be scalable and can handle large datasets and high user concurrency efficiently.

**Active Community and Updates:** Being an Apache project, Superset benefits from a strong community that actively contributes to its development, leading to regular updates and bug fixes.

**Integration with Other Tools:** Superset can be easily integrated with other tools and platforms in the data ecosystem, enhancing its capabilities and extending its use cases.

**SQL-Based Querying:** Users familiar with SQL can write custom queries, giving them greater flexibility in data exploration and analysis.

**Cons:**

**Limited Data Transformation:** While Superset provides basic data manipulation capabilities, it may not be as robust as other ETL tools for complex data transformation tasks.

**Learning Curve for Advanced Features:** Some advanced features and customizations may require more technical expertise, which could pose a learning curve for non-technical users.

**Resource Intensive:** For large-scale deployments with heavy usage, Superset might require substantial hardware resources, including memory and processing power.

**Documentation Gaps:** Although the community actively contributes to the documentation, there might be instances where certain features or use cases are not well-documented.

**Lack of Real-time Data Support:** As of my last update in September 2021, Superset didn't have built-in support for real-time data streaming. Users relying heavily on real-time analytics might find this limiting.

**Data Source Connectivity:** While Superset supports various data sources, the ease of setting up connections and maintaining them can vary, depending on the specific source.

