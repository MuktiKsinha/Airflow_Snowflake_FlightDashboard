<h1 align="center">✈️ Airflow Snowflake Flight Dashboard</h1>

<p align="center">
End-to-end Data Pipeline using Apache Airflow & Snowflake for Flight Analytics
</p>

<hr>

<h2>📌 Project Overview</h2>
<p>
This project demonstrates an end-to-end <b>data pipeline</b> using <b>Apache Airflow</b> and <b>Snowflake</b> 
to build a <b>Flight Analytics Dashboard</b>. It automates data ingestion, transformation, and reporting 
to generate actionable insights.
</p>

<hr>

<h2>🏗️ Architecture</h2>
<ul>
<li><b>Orchestration:</b> Apache Airflow</li>
<li><b>Data Warehouse:</b> Snowflake</li>
<li><b>Data Source:</b> Flight datasets (API / CSV)</li>
<li><b>Transformation:</b> SQL (Snowflake)</li>
<li><b>Visualization:</b> Power BI / Tableau / Streamlit</li>
</ul>

<hr>

<h2>🔄 Workflow</h2>
<ol>
<li>Extract flight data from source</li>
<li>Load raw data into Snowflake staging tables</li>
<li>Transform data using SQL</li>
<li>Create analytical tables (fact & dimension)</li>
<li>Refresh dashboard</li>
</ol>

<hr>

<h2>📂 Project Structure</h2>
<pre>
Airflow_Snowflake_FlightDashboard/
│
├── dags/                  # Airflow DAGs
├── scripts/               # SQL / Python scripts
├── config/                # Configuration files
├── data/                  # Sample datasets
├── requirements.txt       # Dependencies
└── README.md
</pre>

<hr>

<h2>⚙️ Key Features</h2>
<ul>
<li>✅ Automated ETL pipeline using Airflow</li>
<li>✅ Scalable storage with Snowflake</li>
<li>✅ Modular SQL transformations</li>
<li>✅ Error handling & retry mechanisms</li>
<li>✅ Scheduled dashboard updates</li>
</ul>

<hr>

<h2>📊 Use Cases</h2>
<ul>
<li>Flight delay analysis</li>
<li>Airline performance tracking</li>
<li>Airport traffic insights</li>
<li>Trend analysis over time</li>
</ul>

<hr>

<h2>🚀 Getting Started</h2>

<h3>1️⃣ Clone Repository</h3>
<pre><code>git clone https://github.com/MuktiKsinha/Airflow_Snowflake_FlightDashboard.git
cd Airflow_Snowflake_FlightDashboard</code></pre>

<h3>2️⃣ Install Dependencies</h3>
<pre><code>pip install -r requirements.txt</code></pre>

<h3>3️⃣ Configure Airflow</h3>
<ul>
<li>Setup Airflow connections for Snowflake</li>
<li>Update environment variables</li>
</ul>

<h3>4️⃣ Run Airflow</h3>
<pre><code>airflow webserver
airflow scheduler</code></pre>

<h3>5️⃣ Trigger DAG</h3>
<ul>
<li>Open Airflow UI</li>
<li>Enable & trigger DAG</li>
</ul>

<hr>

<h2>🔐 Configuration</h2>
<ul>
<li>Snowflake credentials (Account, User, Password, Warehouse, DB, Schema)</li>
<li>Airflow Connection ID: <code>snowflake_conn</code></li>
</ul>

<hr>

<h2>📈 Dashboard Insights</h2>
<ul>
<li>Total flights</li>
<li>Delayed vs on-time flights</li>
<li>Airline performance</li>
<li>Time-series trends</li>
</ul>

<hr>

<h2>🛠️ Tech Stack</h2>
<ul>
<li>Python</li>
<li>Apache Airflow</li>
<li>Snowflake</li>
<li>SQL</li>
<li>Power BI / Tableau / Streamlit</li>
</ul>

<hr>

<h2>📌 Future Enhancements</h2>
<ul>
<li>Real-time streaming with Kafka</li>
<li>ML model for delay prediction</li>
<li>Data quality checks (Great Expectations)</li>
<li>CI/CD pipeline</li>
</ul>

<hr>

<h2>🤝 Contribution</h2>
<p>Feel free to fork this repo and submit a pull request.</p>

<hr>

<h2>📧 Contact</h2>
<p>
<b>Mukti Sinha</b><br>
GitHub: <a href="https://github.com/MuktiKsinha">https://github.com/MuktiKsinha</a>
</p>

<hr>

<p align="center">⭐ If you like this project, give it a star!</p>
