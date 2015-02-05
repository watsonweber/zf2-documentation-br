# Bem vindo a documentação em português do +Zend Framework 2+

## Informação sobre Lançamentos

Essa documentação é baseada no *Zend Framework 2* (branch master)

## Veja essa documentação online

Nos usamos o projeto [readthedocs.org](http://readthedocs.org/) 
para renderizar de forma online a versão de desenvolvimento da 
documentação do Zend Framework 2.

Você pode ler a documentação online em: 
[http://zf2-documentation-br.readthedocs.org](http://zf2-documentation-br.readthedocs.org/pt/latest/).

## Compilando a Documentação

Compilar a documentação requer o [Sphinx](http://sphinx-doc.org/). Outros requerimentos
são _Pygments_, _docutils_ e _markupsafe_, instaláveis com `pip install`.

Vavegue até o diretório `docs/`, e execute `make` com um dos seguintes paramêtros:

- `epub` - compila a documentação em formato epub (ebook) (requer
  [Calibre](http://calibre-ebook.com/) para compilar versões em epub multi-plataforma)
- `help` - compila em arquivos de ajuda do windows
- `html` - compila a documentação em html
- `info` - compila em página info para Unix
- `latexpdf` - compila a documentação em PDF (requer a ferramenta `latex` funcinando)
- `man` - compila em formato de manuais paraUnix
- `text` - compila em arquivos manual em texto ANSI

Examplos:

```sh
make html
```

você pode realizar a limpeza atraves do comando `make clean`.

## Contribuindo

Caso queira contribuir com a documentação do Zend Framework 2, por favor leia o arquivo
CONTRIBUTING.md.

Se você não sabe por onde começar, ou onde você poderá ajudar mais, por favor veja o
arquivo TODO.md.

## Licença

Os arquivos nesse arquivo são fornecidos sobre a Zend Framework license.
Você pode encontrar uma cópia dessa licença no arquivo LICENSE.txt.

## Agradecimentos

O Time do Zend Framework gostaria de agradecer todos os [contribuidores](https://github.com/zendframework/zf2-documentation/contributors) do 
projeto de documentação do Zend Framework, aos patrocinadores, e você, o usuário do Zend Framework.
O time de tradução da documentação também gostaria de agradecer a todos os [contribuidores](https://github.com/PHPSP/zf2-documentation-br/graphs/contributors)
Visite também a página oficial do Zend Framework em http://framework.zend.com.
