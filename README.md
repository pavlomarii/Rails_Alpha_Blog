## Rails Alpha Blog

##### Prerequisites

The setups steps expect following tools installed on the system.

- Ruby 3.0.2
- Rails 6.1.4.1
- PostgreSQL 12.8

##### 1. Check out the repository

```bash
git clone https://github.com/pavlomarii/Rails_Alpha_Blog.git
```

##### 2. Install dependencies

```bash
yarn install
bundle install
```

##### 3. Setup the local database

Run the following commands to create and setup the database.

```bash
rails db:migrate
```

##### 4. Start the Rails server

You can start the rails server using the command given below.

```bash
rails s
```

And now you can visit the site with the URL http://localhost:3000