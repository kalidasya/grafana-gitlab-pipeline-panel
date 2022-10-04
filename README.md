# Grafana GitlabCI pipelines panel

This plugin creates a panel to visualize GitlabCI pipeline status in Grafana, it requires the GitlabCI pipelines datasource.

I had problems with the existing GitlabCI Pipeline dashboards, they displayed too many branches for each project, required yet another thing to deploy, so I thought why not do it in Grafana. This is the second (well 3rd) iteration, the visualization is limited. 


## Configuration

[Create panel](https://raw.githubusercontent.com/kalidasya/grafana-gitlab-pipeline-panel//docs/grafana-gitlab-create-panel.webm)

## Screenshots

![Dashboard](https://raw.githubusercontent.com/kalidasya/grafana-gitlab-pipeline-panel//master/src/img/dashboard-view.png)
![Panel settings](https://raw.githubusercontent.com/kalidasya/grafana-gitlab-pipeline-panel//master/src/img/settings-page.png)


## Code metrics

[![Code Smells](https://sonarcloud.io/api/project_badges/measure?project=kalidasya_grafana-gitlab-pipeline-panel&metric=code_smells)](https://sonarcloud.io/dashboard?id=kalidasya_grafana-gitlab-pipeline-panel)

[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=kalidasya_grafana-gitlab-pipeline-panel&metric=alert_status)](https://sonarcloud.io/dashboard?id=kalidasya_grafana-gitlab-pipeline-panel)
