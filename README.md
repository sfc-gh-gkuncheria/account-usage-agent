# Snowflake Account Usage Semantic Views

This directory contains semantic models for Snowflake Cortex Analyst on top of `ACCOUNT_USAGE` schema views

## Semantic View Files

### 1. Query Analytics (`query_analytics.yaml`)
**Focus**: Query performance, warehouse usage, and query execution analysis

**Tables Included**:
- `ACCESS_HISTORY` - Object access tracking and audit trail
- `QUERY_ATTRIBUTION_HISTORY` - Query cost attribution and credit usage
- `QUERY_HISTORY` - Complete query execution history and performance metrics
- `WAREHOUSE_LOAD_HISTORY` - Warehouse utilization and load patterns
- `WAREHOUSE_METERING_HISTORY` - Warehouse credit consumption

**Custom Metrics**: 
- Top long-running queries
- Heaviest users by query count and execution time
- Warehouse bottlenecks and queuing analysis
- Query spillers (local and remote storage)
- Credit usage trends and comparisons

### 2. Security & Governance (`security_governance.yaml`)
**Focus**: User management, authentication, access control, and security policies

**Tables Included**:
- `LOGIN_HISTORY` - User login attempts and authentication events
- `SESSIONS` - User session information and client details

### 3. Storage & Cost Management (`storage_cost.yaml`)
**Focus**: Storage utilization, cost tracking, and resource monitoring

**Tables Included**:
- `STAGE_STORAGE_USAGE_HISTORY` - Stage storage utilization tracking
- `STORAGE_USAGE` - Account-level storage consumption metrics
- `TABLE_STORAGE_METRICS` - Table-level storage breakdown and costs
- `WAREHOUSE_METERING_HISTORY` - Warehouse credit consumption tracking

### 4. AI & ML Operations (`ai_ml_ops.yaml`)
**Focus**: Cortex AI services, machine learning operations, and advanced analytics

**Tables Included**:
- `CORTEX_ANALYST_USAGE_HISTORY` - Cortex Analyst service usage
- `CORTEX_DOCUMENT_PROCESSING_USAGE_HISTORY` - Document AI processing
- `CORTEX_FINE_TUNING_USAGE_HISTORY` - Model fine-tuning operations
- `CORTEX_FUNCTIONS_QUERY_USAGE_HISTORY` - AI function usage in queries
- `CORTEX_FUNCTIONS_USAGE_HISTORY` - Aggregated AI function usage
- `CORTEX_SEARCH_DAILY_USAGE_HISTORY` - Vector search service usage
- `CORTEX_SEARCH_SERVING_USAGE_HISTORY` - Search serving operations
- `DATA_QUALITY_MONITORING_USAGE_HISTORY` - Data quality monitoring
- `DOCUMENT_AI_USAGE_HISTORY` - Document AI service usage
- `SNOWPARK_CONTAINER_SERVICES_HISTORY` - Container service usage

### 5. Data Operations (`data_operations.yaml`)
**Focus**: Data loading, task execution, and operational workflows

**Tables Included**:
- `LOAD_HISTORY` - Data loading operations and results
- `LOCK_WAIT_HISTORY` - Locking and concurrency analysis
- `TASK_HISTORY` - Automated task execution tracking
- `AUTOMATIC_CLUSTERING_HISTORY` - Auto-clustering operations
- `MATERIALIZED_VIEW_REFRESH_HISTORY` - Materialized view maintenance
- `COPY_HISTORY` - COPY command execution history
- `DYNAMIC_TABLE_REFRESH_HISTORY` - Dynamic table refresh operations

### 5. **Logical Organization**
Tables are grouped by functional area, making it easier to:
- Find relevant data sources
- Manage and maintain semantic definitions
- Scale individual areas independently
- Improve query performance through focused schemas


## Folder Structure
```
semantic_vws/
├── README.md                           # This documentation
├── query_analytics.yaml               # Query performance and warehouse analytics
├── security_governance.yaml           # Authentication and access control
├── storage_cost.yaml                  # Storage utilization and cost tracking
├── ai_ml_ops.yaml                     # Cortex AI services and ML operations
├── data_operations.yaml               # Data loading and operational workflows
├── database_metadata.yaml             # Database objects and metadata management
└── DASHBOARD_SEMANTIC_LATEST.yaml     # Original consolidated view (deprecated)
```
