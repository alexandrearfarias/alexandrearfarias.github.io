# Chirpy Starter

[![Gem Version](https://img.shields.io/gem/v/jekyll-theme-chirpy)][gem]&nbsp;
[![GitHub license](https://img.shields.io/github/license/cotes2020/chirpy-starter.svg?color=blue)][mit]

When installing the [**Chirpy**][chirpy] theme through [RubyGems.org][gem], Jekyll can only read files in the folders
`_data`, `_layouts`, `_includes`, `_sass` and `assets`, as well as a small part of options of the `_config.yml` file
from the theme's gem. If you have ever installed this theme gem, you can use the command
`bundle info --path jekyll-theme-chirpy` to locate these files.

The Jekyll team claims that this is to leave the ball in the user’s court, but this also results in users not being
able to enjoy the out-of-the-box experience when using feature-rich themes.

To fully use all the features of **Chirpy**, you need to copy the other critical files from the theme's gem to your
Jekyll site. The following is a list of targets:

```shell
.
├── _config.yml
├── _plugins
├── _tabs
└── index.html
```

To save you time, and also in case you lose some files while copying, we extract those files/configurations of the
latest version of the **Chirpy** theme and the [CD][CD] workflow to here, so that you can start writing in minutes.

## Usage

Check out the [theme's docs](https://github.com/cotes2020/jekyll-theme-chirpy/wiki).

## Instalando ambiente

Primeiramente va até a página do [rubyInstaller](https://rubyinstaller.org/downloads/) e instale o Ruby+DevKit usando alguns dos instaladores fornecido pelo site.

> Ao abrir o instaldor e utilizar as configurações padrão, marque o ```Execute ridk install``` para instalar as gems com extensões nativas sem nenhum problema. Durante a instalação via prompt, apenas aperte enter que ele vai instalar tudo necessário.

Após instalar o ruby, verifique se ele está corretamente configurado:

* Abra o prompt de comando pelo iniciar na barra de tarefas e digite o comando:
```cmd
ruby -g
gem -v
```

* Em seguida instale o jekyll na sua máquina ainda no diretório do menu iniciar e confira se foi tudo instalado corretamente
```cmd
gem install jekyll bundler
jekyll -v
```

* Navegue até o diretório do projeto que você trouxe do github e execute dentro do prompt o comando:
```cmd
bundle install
```

Ele vai instalar todas as depêdencias do projeto. Você pode verificar as dependências intaladas pelo arquivo ```Gemfile.lock```.

* Traga os conteúdos de estilo do submodulo do tem chirpy
```cmd
git submodule init
git submodule update
```

Para executar o servidor local e visualizar as alterações feitas no projeto, inicie o servidor local com o comando:
```cmd
bundle exec jekyll s
```

```bundle exec``` é um prefixo para os comandos dentro do jekyll.

## Contributing

This repository is automatically updated with new releases from the theme repository. If you encounter any issues or want to contribute to its improvement, please visit the [theme repository][chirpy] to provide feedback.

## License

This work is published under [MIT][mit] License.

[gem]: https://rubygems.org/gems/jekyll-theme-chirpy
[chirpy]: https://github.com/cotes2020/jekyll-theme-chirpy/
[CD]: https://en.wikipedia.org/wiki/Continuous_deployment
[mit]: https://github.com/cotes2020/chirpy-starter/blob/master/LICENSE
