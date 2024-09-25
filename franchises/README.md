# GoodData Multitenancy series - Franchises Demo

In this quick demo, you will learn how to set up a basic Workspace Hierarchy for Multitenancy use in Gooddata.

This demo focuses on Franchises and is a part of an [article]() about this topic. We will also cover other franchises in the upcoming articles.

## Setup

_This setup expects you to have a running instance of GoodData. If you don't have one, feel free to use our [trial](www.gooddata.com/trial)._


This demo can be easily replicated in 3 steps:
- **[Upload](https://www.gooddata.com/docs/cloud/connect-data/csv/)** the included [supermarket_sales.csv](./supermarket_sales.csv) into your GoodData environment
- **Enter** these three variables into the gooddata.yaml:
    - Hostname
        - The first part of the url e.g., `https://example.trial.cloud.gooddata.com/`
    - GoodData API token
        - Can be [easily created in the GoodData UI](https://www.gooddata.com/docs/cloud/getting-started/create-api-token/).
    - CSV_DS_ID
        - Also has to be included in `analytics/workspaces/franchise_overview/franchise_overview.yaml`
- **Run** `gdc deploy --only workspaces` and `gdc deploy --only workspaces_data_filters` in your terminal.
    - In case you do not have the `gdc` CLI, simply run `pip install gooddata-sdk` and you will have the latest CLI, as it is part of the pip package.

### Upload

Step by step?

### Entering the Variables

Step by step?

### Running

Step by step?