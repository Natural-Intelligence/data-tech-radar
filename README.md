# data-tech-radar

- [Orchestration](#Orchestration)
- [Distributed Computing](#Distributed-Computing)
- [Query Engine](#Query-Engine)
- [Data Lakehouse/Warehouse](#Data-Lakehouse%2FWarhouse)

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

## Data Lakehouse/Warehouse
