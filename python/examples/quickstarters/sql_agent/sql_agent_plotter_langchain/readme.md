# SQL Agent Guide

This guide provides detailed steps to create a SQL agent that leverages Langchain, Composio, and ChatGPT to execute SQL queries, document them and plot graphs based on them. Ensure you have Python 3.8 or higher installed. 
Here's the coding guide in our documentation: [Guide](https://docs.composio.dev/guides/examples/sql-agent)

# Sample Output:
![](https://github.com/composiohq/composio/blob/master/python/examples/quickstarters/sql_agent/sql_agent_plotter_langchain/sql_agent.gif)

## Sample Output plot
![](https://github.com/composiohq/composio/blob/master/python/examples/quickstarters/sql_agent/sql_agent_plotter_langchain/example_plot_based_on_db.png)
## Steps to Run

**Navigate to the Project Directory:**
Change to the directory where the `setup.sh`, `main.py`, `requirements.txt`, and `README.md` files are located. For example:
```sh
cd path/to/project/directory
```

### 1. Run the Setup File
Make the setup.sh Script Executable (if necessary):
On Linux or macOS, you might need to make the setup.sh script executable:
```shell
chmod +x setup.sh
```
Execute the setup.sh script to set up the environment and install dependencies:
```shell
./setup.sh
```
Now, fill in the `.env` file with your secrets.

### 2. Run the Python Script
```shell
python cookbook/examples/sql_agent/main.py
```
Your database operations should be performed as described by the script, with SQL queries executed and logged accordingly.

Note: We have a dummy database called company.db with a table named products. Feel free to use this database for reference and execute queries on it to understand the agent's functionality better.
