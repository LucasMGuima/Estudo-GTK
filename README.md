# Aula 01
---
## Arquivos
`com.example.TextViewer.json`: Manifesto Flatpak do aplicativo.
Pode ser usado para definir as dependências do projeto. O
manifesto padrão depende da ultima versão estável da plataforma
GNOME. Pode-se adicionar dependências amais não providenciadas
pelo GNOME.

`meson.build`: Este é o arquivo Meson principal, que defino
como e oque construir da aplicação.

`src`: Este é o diretório com os arquivos fonte da aplicação,
como também os arquivos de definição de UI.

`src/text-viewer.gresource.xml`: O manifesto GResource para assets
que serão integrados ao projeto usando o `glib-compile-resources`.

`po/POTFILES`: A lista de arquivos contendo traduções, strings
visíveis para o usuário.

`data/com.example.TextViewer.gschema.xml`: O arquivo esquema para
a configuração da aplicação.

`data/com.example.TextViewer.desktop.in`: O arquivo de estrada
desktop para a aplicação.

`data/com.example.TextViewer.appdata.xml.in`: O metadado da
aplicação usado por lojas de aplicativos e distribuidores de
aplicações.
