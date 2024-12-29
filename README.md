# Sinatra App

## To run

In directory

```bash
docker compose up
```

```bash
bundle install
```

```bash
rake db:create
```

```bash
rake db:migrate
```

### Running on PORT => 9393

```bash
shotgun config.ru
```

OR

### Running on PORT => 3000

```bash
puma -C config/puma.rb
```

Enjoy ☕️