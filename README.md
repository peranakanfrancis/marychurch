[![Netlify Status](https://api.netlify.com/api/v1/badges/2e8ba43b-be12-4737-8b0a-0a51d4b4c82e/deploy-status)](https://app.netlify.com/sites/marychurch/deploys)

![source](https://www.mybluelinux.com/how-create-bootstrap-tables-in-hugo/)

### Striped table with bootstrap dark header and hoovered
**shortcode:**

{{< table table_class="table table-striped table-hover" thead_class="table-dark" >}}
| # | First          | Last     | Handle   |
|---|----------------|----------|----------|
| 1 | Mark           | Otto     | @mdo     |
| 2 | Jacob          | Thornton | @fat     |
| 3 | Larry the Bird |          | @twitter |
{{< table >}}


### Table hoover with header in bootstrap info color
**shortcode:**

{{< table table_class="table table-hover" thead_class="table-info" >}}
| # | First          | Last     | Handle   |
|---|----------------|----------|----------|
| 1 | Mark           | Otto     | @mdo     |
| 2 | Jacob          | Thornton | @fat     |
| 3 | Larry the Bird |          | @twitter |
{{< /table >}}


### Tables without borders
**shortcode:**

{{< table table_class="table table-hover table-borderless" thead_class="table-info" >}}
| # | First          | Last     | Handle   |
|---|----------------|----------|----------|
| 1 | Mark           | Otto     | @mdo     |
| 2 | Jacob          | Thornton | @fat     |
| 3 | Larry the Bird |          | @twitter |
{{< /table >}}

### Small tables
Add .table-sm to make any .table more compact by cutting all cell padding in half.

**shortcode:**

{{< table table_class="table table-sm" thead_class="table-warning" >}}
| # | First          | Last     | Handle   |
|---|----------------|----------|----------|
| 1 | Mark           | Otto     | @mdo     |
| 2 | Jacob          | Thornton | @fat     |
| 3 | Larry the Bird |          | @twitter |
{{< /table >}}
