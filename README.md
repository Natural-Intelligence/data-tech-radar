# data-tech-radar

- [Orchestration](#Orchestration)
- [Distributed Computing](#Distributed-Computing)
- [Query Engine](#Query-Engine)
- [Data Lakehouse and Warehouse](#Data-Lakehouse-and-Warehouse)
- [Real-Time Analytics Database](#Real-Time-Analytics-Database)
- [Messaging](#Messaging)
- [Stream Processing](#Stream-Processing)
- [Data Formats](#Data-Formats)
- [Feature Store](#Feature-Store)
- [Experiment Tracking](#Experiment-Tracking)
- [ML Tracking](#ML-Tracking)
- [AutoML](#AutoML)

## Orchestration

[Apache Airflow](https://github.com/apache/airflow) - Airflow is a platform created by the community to programmatically author, schedule and monitor workflows.

[Apache Liminal](https://github.com/apache/incubator-liminal) - Liminal's goal is to operationalise the machine learning process, allowing data scientists to quickly transition from a successful experiment to an automated pipeline of model training, validation, deployment and inference in production.

[Apache Hop](https://github.com/apache/incubator-hop) - "The Hop Orchestration Platform, or Apache Hop (Incubating), aims to facilitate all aspects of data and metadata orchestration. Hop aims to be the future of data integration. Visual development enables developers to be more productive than they can be through
code."

[Apache DolphinScheduler](https://github.com/apache/dolphinscheduler) - A distributed and easy-to-extend visual workflow scheduler system. Dedicated to solving the complex task dependencies in data processing, making the scheduler system out of the box for data processing.

[Apache Kubeflow](https://github.com/kubeflow/kubeflow) - The Kubeflow project is dedicated to making deployments of machine learning (ML) workflows on Kubernetes simple, portable and scalable. The goal is not to recreate other services, but to provide a straightforward way to deploy best-of-breed open-source systems
for ML to diverse infrastructures.

[mlflow](https://github.com/mlflow/mlflow) - MLflow is an open source platform to manage the ML lifecycle, including experimentation, reproducibility, deployment, and a central model registry.

[ZenML](https://github.com/zenml-io/zenml) - ZenML is an extensible, open-source MLOps framework to create production-ready machine learning pipelines. It has a simple, flexible syntax, is cloud and tool agnostic, and has interfaces/abstractions that are catered towards ML workflows.

[Metaflow](https://github.com/Netflix/metaflow) - Metaflow helps you design your workflow, run it at scale, and deploy it to production. It versions and tracks all your experiments and data automatically. It allows you to inspect results easily in notebooks.

[Flyte](https://github.com/flyteorg/flyte) - "Flyte makes it easy to create concurrent, scalable, and maintainable workflows for machine learning and data processing.
Flyte is used in production at Lyft, Spotify, Freenome and others."

[ClearML](https://github.com/allegroai/clearml) - ClearML is the only open source tool to manage all your MLOps in a unified and robust platform providing collaborative experiment management, powerful orchestration, easy-to-build data stores, and one-click model deployment. ClearML is the foundation for your data science team.

[Pachyderm](https://github.com/pachyderm/pachyderm/) - Pachyderm provides the data layer that allows machine learning teams to productionize and scale their machine learning lifecycle. With Pachyderm’s industry leading data versioning, pipelines and lineage teams gain data driven automation, petabyte scalability and end-to-end reproducibility. Teams using Pachyderm get their ML projects to market faster, lower data processing and storage costs, and can more easily meet regulatory compliance requirements

[Prefect](https://github.com/PrefectHQ/prefect) - The prefect Python library includes everything you need to design, build, test, and run powerful data applications. Instantly upgrade your existing code with workflow best practices, and use the Prefect UI to orchestrate and monitor everything.

[Ploomber](https://github.com/ploomber/ploomber) - Ploomber is a framework to build collaborative and modular pipelines; it integrates with Jupyter but you can use it with any other editor.
Ploomber eliminates the notebook refactoring problem: data teams prototype their work in Jupyter notebooks and then refactor the code for deployment.

[Amazon SageMaker](https://aws.amazon.com/sagemaker/) - Amazon SageMaker helps data scientists and developers to prepare, build, train, and deploy high-quality machine learning (ML) models quickly by bringing together a broad set of capabilities purpose-built for ML.

[Google Cloud Vertex AI](https://cloud.google.com/vertex-ai/) - Vertex AI brings together the Google Cloud services for building ML under one, unified UI and API. In Vertex AI, you can now easily train and compare models using AutoML or custom code training and all your models are stored in one central model repository. These models can now be deployed to the same endpoints on Vertex AI.

## Distributed Computing

[Apache Spark](https://github.com/apache/spark) - Apache Spark is a multi-language engine for executing data engineering, data science, and machine learning on single-node machines or clusters.

[Amazon EMR](https://aws.amazon.com/emr/) - Amazon EMR is a platform for rapidly processing, analyzing, and applying machine learning (ML) to big data using open-source frameworks.

[AWS Batch](https://aws.amazon.com/batch/) - AWS Batch enables developers, scientists, and engineers to easily and efficiently run hundreds of thousands of batch computing jobs on AWS.

[AWS Fargate](https://aws.amazon.com/fargate/) - AWS Fargate is a serverless, pay-as-you-go compute engine that lets you focus on building applications without managing servers. AWS Fargate is compatible with both Amazon Elastic Container Service (ECS) and Amazon Elastic Kubernetes Service (EKS).

[dbt](https://github.com/dbt-labs/dbt-core) - dbt (data build tool) enables analytics engineers to transform data in their warehouses by simply writing select statements. dbt handles turning these select statements into tables and views.

[Fiber](https://github.com/uber/fiber/) - Fiber is a Python-based distributed computing library for modern computer clusters. Instead of programming your desktop or laptop, now you can program the whole computer cluster. It was developed to power large scale parallel scientific computation projects like POET.

[Ray](https://github.com/ray-project/ray) - Ray is an open source project that makes it ridiculously simple to scale any compute-intensive Python workload — from deep learning to production model serving. With a rich set of libraries and integrations built on a flexible distributed execution framework, Ray makes distributed computing easy and accessible to every engineer.

[SCOOP](https://github.com/soravux/scoop) - SCOOP (Scalable COncurrent Operations in Python) is a distributed task module allowing concurrent parallel programming on various environments, from heterogeneous grids to supercomputers.

## Query Engine

[Amazon Athena](https://aws.amazon.com/athena/) - Amazon Athena is an interactive query service that makes it easy to analyze data in Amazon S3 using standard SQL. Built on Presto, runs standard SQL. Athena is serverless, so there is no infrastructure to manage, and you pay only for the queries that you run. 

[Presto](https://github.com/prestodb/presto) - Presto is an open source distributed SQL query engine for running interactive analytic queries against data sources of all sizes ranging from gigabytes to petabytes. Presto was designed and written from the ground up for interactive analytics and approaches the speed of commercial data warehouses while scaling to the size of organizations like Facebook.

[trino](https://github.com/trinodb/trino) - Fast distributed SQL query engine for big data analytics that helps you explore your data universe

## Data Observability

[AWS Glue](https://aws.amazon.com/glue/) - The AWS Glue Data Catalog is your persistent metadata store. It is a managed service that lets you store, annotate, and share metadata in the AWS Cloud in the same way you would in an Apache Hive metastore.

[DataHub](https://github.com/linkedin/datahub) - The Metadata Platform for the Modern Data Stack - Data ecosystems are diverse — too diverse. DataHub's extensible metadata platform enables data discovery, data observability and federated governance that helps you tame this complexity."

[OpenMetadata](https://github.com/open-metadata/OpenMetadata) - OpenMetadata is an Open Standard for Metadata. A Single place to Discover, Collaborate, and Get your data right.

[Apache Superset](https://github.com/apache/superset) - Apache Superset is a modern data exploration and visualization platform

[Metabase](https://github.com/metabase/metabase) - The easy, open source way for everyone in your company to ask questions and learn from data.

[Hue](https://github.com/cloudera/hue) - Hue is an open source SQL Assistant for Databases & Data Warehouses

[Metacat](https://github.com/Netflix/metacat) - Metacat is a unified metadata exploration API service. You can explore Hive, RDS, Teradata, Redshift, S3 and Cassandra. Metacat provides you information about what data you have, where it resides and how to process it. Metadata in the end is really data about the data. So the primary purpose of Metacat is to give a place to describe the data so that we could do more useful things with it.

[Apache Atlas](https://github.com/apache/atlas) - Atlas is a scalable and extensible set of core foundational governance services – enabling enterprises to effectively and efficiently meet their compliance requirements within Hadoop and allows integration with the whole enterprise data ecosystem.

[Monte Carlo](https://www.montecarlodata.com/") - Monte Carlo’s Data Observability platform helps your team increase in trust in data by eliminating data downtime.

[Optimus](https://github.com/hi-primus/optimus) - Optimus focused on giving you the best tools for all your data processing needs. From data quality, plotting, parsing dates, URLs, email, and NLP preparation.

[Data Sentinel](https://www.data-sentinel.com/) - Data Sentinel - Effective solutions driven by machine-learning, that help you comply with data privacy regulations, manage data risk, govern data policies, and produce pristine data to help you grow your business. Satisfaction guaranteed.

## Data Lakehouse and Warehouse

[Amazon Redshift](https://aws.amazon.com/redshift/) - Analyze all of your data with the fastest and most widely used cloud data warehouse

[Apache Hudi](https://github.com/apache/hudi) - Hudi brings transactions, record-level updates/deletes and change streams to data lakes!

[Delta Lake](https://github.com/delta-io/delta) - Delta lake is an open-source project that enables building a Lakehouse Architecture on top of existing storage systems such as S3, ADLS, GCS, and HDFS.

[Firebolt](https://www.firebolt.io/) - Deliver production grade data applications & analytics with Firebolt - the cloud data warehouse of choice for modern data engineering & dev teams

[dremio](https://www.dremio.com/) - Ad-hoc, mission-critical BI directly on cloud data lake storage, without copying the data into warehouses, marts, extracts or cubes. Data analysts and data scientists are empowered to discover, curate, analyze, and share datasets with a self-service mindset. Users can build interactive dashboards through native Dremio connectors in tools, such as Tableau and Power BI.

[Snoflake](https://www.snowflake.com/) - Get the performance, flexibility, and near-infinite scalability to easily load, integrate, analyze, and securely share your data. Snowflake is a fully managed service that’s simple to use. Snowflake is your solution for data warehousing, data lakes, data engineering, data science, data application development, and securely sharing and consuming shared data.

[upsolvr](https://www.upsolver.com/) - The quickest path from streams to analytics-ready tables. Easily and affordably transform streaming data into live tables on top of cloud object storage. Query directly on the lake or continuously output tables to external analytics systems.

## Real-Time Analytics Database

[Apache Druid](https://github.com/apache/druid) - Apache Druid is a high performance real-time analytics database.

[Apache Pinot](https://github.com/apache/pinot) - Realtime distributed OLAP datastore, designed to answer OLAP queries with low latency

[ClickHouse](https://github.com/ClickHouse/ClickHouse) - ClickHouse is an open-source, high performance columnar OLAP database management system for real-time analytics using SQL.

[Rockset](https://rockset.com/) - Build modern data applications and live dashboards in record time. The real-time

## Messaging

[Apache Kafka](https://github.com/apache/kafka) - Apache Kafka is an open-source distributed event streaming platform used by thousands of companies for high-performance data pipelines, streaming analytics, data integration, and mission-critical applications.

[Amazon Kinesis](https://aws.amazon.com/kinesis/) - Amazon Kinesis makes it easy to collect, process, and analyze real-time, streaming data so you can get timely insights and react quickly to new information.

[Amazon MSK](https://aws.amazon.com/msk/) - Amazon MSK - Securely stream data with a fully managed, highly available Apache Kafka service

[Apache Pulsar](https://github.com/apache/pulsar) - Apache Pulsar is a cloud-native, distributed messaging and streaming platform originally created at Yahoo! and now a top-level Apache Software Foundation project

[Apache EventMesh](https://github.com/apache/incubator-eventmesh) - A dynamic cloud-native eventing infrastructure used to decouple the application and backend middleware layer, which supports a wide range of use cases that encompass complex multi-cloud, widely distributed topologies using diverse technology stacks.

## Stream Processing

[Apache Kafka Connect](https://github.com/apache/kafka/tree/trunk/connect) - Kafka Connect allows you to build connectors to integrate Apache Kafka with other apps and data systems.

[Apache Flink](https://github.com/apache/flink) - Apache Flink is a framework and distributed processing engine for stateful computations over unbounded and bounded data streams. Flink has been designed to run in all common cluster environments, perform computations at in-memory speed and at any scale.

[Mantis](https://github.com/netflix/mantis/) - Mantis is a platform to build an ecosystem of realtime stream processing applications. Similar to micro-services deployed in a cloud, Mantis applications (jobs) are deployed on the Mantis platform. The Mantis platform provides the APIs to manage the life cycle of jobs (like deploy, update, and terminate), manages the underlying resources by containerizing a common pool of servers.

[Debezium](https://github.com/debezium/debezium) - Debezium is an open source distributed platform for change data capture. Start it up, point it at your databases, and your apps can start responding to all of the inserts, updates, and deletes that other apps commit to your databases. Debezium is durable and fast, so your apps can respond quickly and never miss an event, even when things go wrong.

## Data Formats

[Apache Parquet](https://github.com/apache/parquet-mr) - Apache Parquet is a columnar storage format available to any project in the Hadoop ecosystem, regardless of the choice of data processing framework, data model or programming language.

[Apache Iceberg](https://github.com/apache/iceberg) - Apache Iceberg is an open table format for huge analytic datasets. Iceberg adds tables to compute engines including Spark, Trino, PrestoDB, Flink and Hive using a high-performance table format that works just like a SQL table.

[Zstandard](https://github.com/facebook/zstd) - Zstandard, or zstd as a short version, is a fast lossless compression algorithm, targeting real-time compression scenarios at zlib-level and better compression ratios. It's backed by a very fast entropy stage, provided by Huff0 and FSE library.

## Feature Store

[Feast](https://github.com/feast-dev/feast) - Serve your features in production. Feast is an open-source feature store. It is the fastest path to operationalizing analytic data for model training and online inference.

[Hopsworks](https://github.com/logicalclocks/hopsworks) - Hopsworks Feature Store provides an open ecosystem that connects to the largest number of data storage, data pipelines, and data science platforms. With support for any Python or Spark environment, there is no vendor lock-in.

[Feathr](https://github.com/linkedin/feathr) - Feathr is the feature store that is used in production in LinkedIn for many years and was open sourced in April 2022.

## Experiment Tracking

[AimStack](https://github.com/aimhubio/aim) - The open-source tool for ML experiment comparison.

[ClearML](https://github.com/allegroai/clearml) - ClearML is the only open source tool to manage all your MLOps in a unified and robust platform providing collaborative experiment management, powerful orchestration, easy-to-build data stores, and one-click model deployment. ClearML is the foundation for your data science team.

[DAGsHub](https://dagshub.com/) - Leverage popular open source tools to version datasets & models, track experiments, label data, and visualize results.

[neptune.ai](https://neptune.ai/) - Experiment tracking and model registry for production teams. Log, store, query, display, organize, and compare all your model metadata in a single place.

## ML Tracking

[DVC](https://github.com/iterative/dvc) - Open-source Version Control System for Machine Learning Projects. DVC tracks ML models and data sets. DVC is built to make ML models shareable and reproducible. It is designed to handle large files, data sets, machine learning models, and metrics as well as code.

[Evidently AI](https://github.com/evidentlyai/evidently) - We build tools to evaluate, test and monitor machine learning models, so you don't have to.

[Amazon SageMaker](https://aws.amazon.com/sagemaker/model-monitor/) - Amazon SageMaker Model Monitor

[Qwak](https://www.qwak.com/) - A fully managed platform that unifies ML engineering and data operations - providing agile infrastructure that enables the continuous productionization of ML models at scale.

[Aporia](https://www.aporia.com/) - Create customized monitors for your machine learning models with our magically-simple monitor builder, and get alerts for issues like concept drift, model performance degradation, bias and more.

[Arize AI](https://arize.com/) - Automatically discover issues, diagnose problems, and improve models with Arize’s machine learning (ML) observability platform

[WhyLabs](https://whylabs.ai/) - Run AI with Certainty. Enable AI Observability to achieve healthy models, fewer incidents, and happy customers.

[Qualdo](https://www.qualdo.ai/) - We are a leader in Data Quality & ML Model for enterprises adopting a multi-cloud, ML and modern data management ecosystem.

[fiddler](https://www.fiddler.ai/) - Build Trust into AI - ML Monitoring. Explainability. Bias Detection. Responsible AI.

[Censius](https://censius.ai/) - Monitor, explain, and optimize ML models. Proactively detect and resolve performance regression, poor data quality, and model drifts to build reliable machine learning models.

[DataRobot](https://www.datarobot.com/) - AI Cloud is a new approach built for the demands, challenges and opportunities of AI today. A single system of record, accelerating the delivery of AI to production for every organization. All users collaborate in a unified environment built for continuous optimization across the entire AI lifecycle.

## AutoML

[Google AutoML](https://github.com/google/automl) - Train high-quality custom machine learning models with minimal effort and machine learning expertise.

[MLBox](https://github.com/AxeldeRomblay/MLBox) - "MLBox is a powerful Automated Machine Learning python library. Fast reading and distributed data preprocessing/cleaning/formatting. Highly robust feature selection and leak detection. Accurate hyper-parameter optimization in high-dimensional space. State-of-the art predictive models for classification and regression (Deep Learning, Stacking, LightGBM,…). Prediction with models interpretation.

[Model Search](https://github.com/google/model_search) - Model search (MS) is a framework that implements AutoML algorithms for model architecture search at scale. It aims to help researchers speed up their exploration process for finding the right model architecture for their classification problems (i.e., DNNs with different types of layers).

[Amazon Personalize](https://aws.amazon.com/personalize/) - Amazon Personalize enables developers to build applications with the same machine learning (ML) technology used by Amazon.com for real-time personalized recommendations – no ML expertise required.

[H2O ai](https://www.h2o.ai/products/h2o-driverless-ai/) - H2O Driverless AI empowers data scientists to work on projects faster and more efficiently by using automation to accomplish key ML tasks in just minutes or hours, not months. By delivering automatic feature engineering, model validation, tuning, selection and deployment, machine learning interpretability, bring your own recipe, time-series and automatic pipeline generation for model scoring.

## Python web frameworks

[FastAPI](https://github.com/tiangolo/fastapi) - FastAPI is a modern, fast (high-performance), web framework for building APIs with Python 3.6+ based on standard Python type hints.
[Flask](https://github.com/pallets/flask) - Flask is a lightweight WSGI web application framework. It is designed to make getting started quick and easy, with the ability to Scale Up to complex applications. It began as a simple wrapper around Werkzeug and Jinja and has become one of the most popular Python web application frameworks.
[Streamlit](https://github.com/streamlit/streamlit) - A faster way to build and share data apps. Streamlit turns data scripts into shareable web apps in minutes. All in pure Python. No front‑end experience required. "Turn R&D into ROI with more models into production  At scale, faster, with increased accuracy
[Seldon](https://github.com/SeldonIO/seldon-core) - Seldon reduces time-to-value so models can get to work faster. Scale with confidence and minimise risk through interpretable results and transparent model performance."
