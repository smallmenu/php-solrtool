# php-solrtool

## solr-delta.php 增量索引脚本

通过计划任务运行增量索引

```
30 */4 * * * /usr/bin/php /usr/local/bin/solr-delta.php -c index1 >> /var/log/solr-delta-index1.log
0 */4 * * * /usr/bin/php /usr/local/bin/solr-delta.php -c index2 >> /var/log/solr-delta-index2.log
```
