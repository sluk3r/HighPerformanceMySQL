





This appendix shows you how to invoke EXPLAIN to get information about the query

execution plan, and how to interpret the output. The EXPLAIN command is the main

way to find out how the query optimizer decides to execute queries. This feature has

limitations and doesn’t always tell the truth, but its output is the best information

available, and it’s worth studying so you can learn how your queries are executed.

Learning to interpret EXPLAIN will also help you learn how MySQL’s optimizer works

