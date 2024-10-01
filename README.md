# Gen3 Grafana Dashboards

This repository contains generic Grafana dashboards for monitoring and visualizing various metrics in Gen3 environments. Each dashboard is stored in JSON format, making it easy to import into any Grafana instance.

## Dashboards

The dashboards in this repository are designed to be reusable and cover common metrics for monitoring Gen3 components, such as:

- **Downloads, Requests, and logins**
- **Portal Traffic Stats**
  
More dashboards will be added as they are developed.

## How to Use

### Importing a Dashboard

To import a dashboard from this repository:

1. Download the desired JSON file.
2. Open your Grafana instance and navigate to **Dashboards** > **Manage**.
3. Click on the **Import** button.
4. Upload the downloaded JSON file or paste its content into the import panel.
5. Click **Load** and configure the data sources as required.

### Customization

Each dashboard is designed to be generic but may require some customization based on your environment. Ensure you:

- **Update data sources**: After importing a dashboard, configure the correct data sources (e.g., Prometheus, Loki, Elasticsearch).
- **Adjust variables**: Some dashboards use template variables that need to be adjusted for your specific environment (e.g., cluster names, namespaces).

## Contributions

Feel free to contribute to this repository by submitting pull requests for new dashboards, improvements, or bug fixes.

### How to Contribute

All changes to the grafana-dashboards repository should be made through pull requests.

1. Fork the [grafana-dashboards repository](https://github.com/uc-cdis/grafana-dashboards) on GitHub to make your changes.

4. Run the relevant tests for the features added or bugs fixed by your pull request.

5. Write a descriptive commit message.

6. Commit and push your changes to your fork.

7. Open a pull request with these changes.

8. Your pull request will be reviewed by a project maintainer and merged if it is deemed appropriate.
