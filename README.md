# FrontendSwing
Este projeto é uma aplicação Java Swing que demonstra a personalização de componentes utilizando a biblioteca FlatLaf. Ele inclui uma tabela com cabeçalhos customizados e rolagem estilizada.

## Funcionalidades
* Customização de Estilos com FlatLaf: Utiliza FlatClientProperties para aplicar estilos personalizados em componentes Swing.
 
* Tabela com Cabeçalhos Customizados: Implementa CheckBoxTableHeaderRenderer e TableHeaderAlignment para cabeçalhos de tabela personalizados.
 
* Dados de Teste: Popula a tabela com uma lista de fabricantes de automóveis como dados de exemplo.
## Tecnologias Utilizadas
* Java Swing: Para a criação da interface gráfica.

* FlatLaf: Para a customização do tema e estilos dos componentes Swing.
 
* FlatRobotoFont: Para configurar a fonte padrão da aplicação.
 
Como Executar
Clone o repositório:

~~~
git clone https://github.com/seu-usuario/FrontendSwing.git
~~~
Navegue até o diretório do projeto:

~~~
cd FrontendSwing
~~~
Compile e execute a aplicação:
~~~
javac -cp .:path/to/flatlaf-0.43.jar frontendswing/Main.java
java -cp .:path/to/flatlaf-0.43.jar frontendswing.Main
~~~
## Estrutura do Código
* Main.java: Classe principal que inicializa a interface gráfica.

* CheckBoxTableHeaderRenderer.java: Customiza o cabeçalho da tabela com checkboxes.
  
*TableHeaderAlignment.java: Alinha o texto nos cabeçalhos da tabela.

Capturas de Tela
Adicione aqui capturas de tela da sua aplicação.

## Contribuições
Contribuições são bem-vindas! Por favor, abra uma issue ou envie um pull request.

## Licença
Este projeto está licenciado sob a Licença MIT. Veja o arquivo LICENSE para mais detalhes.

Créditos [Raven Laing](https://github.com/DJ-Raven)
