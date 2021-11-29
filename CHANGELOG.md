# dbt_twitter_organic_source v0.1.0

The original release! This package contains staging models, designed to work simultaneously with our [Twitter Organic modeling package](https://github.com/fivetran/dbt_twitter_organic) and our [Social Media Reporting package](https://github.com/fivetran/dbt_social_media_reporting). The staging models name columns consistently across all packages:
 * Boolean fields are prefixed with `is_` or `has_`
 * Timestamps are appended with `_timestamp`
 * ID primary keys are prefixed with the name of the table. For example, the account table's ID column is renamed `account_id`.