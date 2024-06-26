[www]
user = www-data
group = www-data
listen = 0.0.0.0:9000
listen.owner = www-data
listen.group = www-data
listen.mode = 0660
pm = dynamic
pm.max_children = 5
pm.start_servers = 2
pm.min_spare_servers = 1
pm.max_spare_servers = 3
security.limit_extensions = .php .php3 .php4 .php5 .php7 .html .htm
