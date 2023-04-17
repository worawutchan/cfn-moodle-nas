# cfn-moodle-nas

![Moodle-AWS-Diagram](https://user-images.githubusercontent.com/18388161/232433766-f7eb7d46-40bb-45a2-88af-4aa2979be479.jpg)

- Use EC2 as NAS server instead of EFS for small size of Moodle data (EFS limited Throuput for small data size)
- Use RDS Aurora Mysql
- Required to configure Moodle to use application cache for Memcache
