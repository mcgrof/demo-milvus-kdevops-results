# Milvus kdevops Test Results Demo

This repository contains test results from a kdevops demonstration of Milvus performance testing using MinIO storage with multiple target filesystem support.

## Test Results

### Multi-Filesystem Results
- **HTML Report**: [View Report](https://htmlpreview.github.io/?https://github.com/mcgrof/demo-milvus-kdevops-results/blob/master/results-multifs/benchmark_report.html) | [Raw HTML](results-multifs/benchmark_report.html)
- **Summary**: [results-multifs/benchmark_summary.txt](results-multifs/benchmark_summary.txt)
- **Performance Visualizations**:
  - [Filesystem Comparison](results-multifs/filesystem_comparison.png)
  - [Index Performance](results-multifs/index_performance.png)
  - [Insert Performance](results-multifs/insert_performance.png)
  - [Query Performance](results-multifs/query_performance.png)
  - [Performance Matrix](results-multifs/performance_matrix.png)

### Simple Results
- **HTML Report**: [View Report](https://htmlpreview.github.io/?https://github.com/mcgrof/demo-milvus-kdevops-results/blob/master/results-simple/benchmark_report.html) | [Raw HTML](results-simple/benchmark_report.html)
- **Summary**: [results-simple/benchmark_summary.txt](results-simple/benchmark_summary.txt)
- **Performance Visualizations**:
  - [Performance Heatmap](results-simple/graphs/performance_heatmap.png)
  - [Performance Trends](results-simple/graphs/performance_trends.png)

## About

This demo showcases Milvus vector database performance testing across different filesystem configurations using kdevops infrastructure. The tests were conducted with MinIO as the object storage backend, demonstrating how various filesystem types affect Milvus performance metrics including insertion, indexing, and query operations.

The results provide insights into optimal filesystem selection for Milvus deployments in different environments.