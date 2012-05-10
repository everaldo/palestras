palestras
=========

Repositório de Palestras e Apresentações


Instalação do Landslide
_________

https://github.com/adamzap/landslide


Ubuntu
______

* Dependências

    $ sudo apt-get install python-pygments
    $ sudo apt-get install python-jinja2
    $ sudo apt-get install python-docutils
    $ sudo apt-get install python-markdown
    $ sudo apt-get install python-setuptools
    $ sudo apt-get install libssl0.9.8:i386


* PrinceXML (para gerar PDF)

http://www.princexml.com

http://www.princexml.com/download/prince_8.0-1ubuntu10.04_i386.deb

* Landslide

    $ git clone https://github.com/adamzap/landslide.git
    $ cd landslide
    $ python setup.py build
    $ sudo python setup.py install


* Geração dos slides

    $ landslide config_html.cfg //gera um único arquivo HTML
    $ landslide config_pdf.cfg //gera PDF










