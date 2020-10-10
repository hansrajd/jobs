## List of companies and careers link to search/apply for jobs

| Company name | Careers page               |
|--------------|----------------------------|
| Facebook     | https://www.facebook.com/careers/ |
| Apple        | https://www.apple.com/jobs/us/ |
| Amazon       | https://www.amazon.jobs/en/ |
| Netflix      | https://jobs.netflix.com |
| Google       | https://careers.google.com |

## Roadmap
Expectation is to be able to search for number of open positions with some simple queries like some tags and location.
```bash
./get_jobs.py --tags python --location India
```
Above query should give below result
```bash
Company  |  Tags   |  Location | Open positions
--------------------------------------------
Facebook |  python |  India    | 20
Apple    |  python |  India    | 10
```

Without any search filter, it should show global counts
```bash
./get_jobs.py
```
Above query should give below result
```bash
Company  |  Open positions
--------------------------
Facebook |  200
Apple    |  150
```
