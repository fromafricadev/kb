# users

### SQL Schema

```sql
CREATE TABLE `users` (
	`id` int NOT NULL AUTO_INCREMENT,
	`username` text,
	`email` text,
	`password` text,
	`phone` text,
	PRIMARY KEY (`id`)
) ENGINE InnoDB,
  CHARSET utf8mb4,
  COLLATE utf8mb4_0900_ai_ci;
```
