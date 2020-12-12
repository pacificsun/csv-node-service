# Make a table with query

CREATE TABLE category(
id integer NOT NULL,
name VARCHAR(255) NOT NULL,
description VARCHAR(255),
created_at DATE);

# Make a test CSV file and put some values

id,name,description,createdAt
1,Node.js,JavaScript runtime environment,2019-09-03
2,Vue.js,JavaScript Framework for building UI,2019-09-06
3,Angular.js,Platform for building mobile & desktop web app,2019-09-09
