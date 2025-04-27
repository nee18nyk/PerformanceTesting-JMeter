# PerformanceTesting-JMeter
Https Login test was performed with cookie manage. Regular Expressions is demonstrated in attached .jmx script. Size and Duration Assertions were used to demonstrate performance metrics with pass and failed assertions. Other functional assertions are also demonstrated with Response Assertion. Debug sampler was used to further prepare variables that can be used with single regex extractor

Concurrency thread group was tested. attached with .jmx script, snapshots of results and analysis report

Ultimate thread group was tested. attached with .jmx script, snapshots of results and analysis report

Some important listeners were covered: Aggregate report, view results tree, assertion results and graph results

For webtours jmx:
Install microfocus webtours application on system and run the app via local ip on port on 1080
Data driven via csv data config
groovy script written to compare response assertions that is used with If controller
