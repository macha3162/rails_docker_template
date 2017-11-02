# docker rails template

## to initialize from base

```bash
git clone https://github.com/macha3162/rails_docker_template.git
cd rails_docker_template
script/init && script/bootstrap
```

## to bootstrap after clone

```bash
git clone https://github.com/macha3162/rails_docker_template.git
cd rails_docker_template
git checkout -b ruby-2.4.2-rails-5.0.6 origin/ruby-2.4.2-rails-5.0.6 && script/bootstrap
```

## to develop

```bash
docker-compose up -d
docker-compose exec spring rails db:migrate
```

## License

MIT
