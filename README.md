GAMEVAULT - pacote inicial para publicação

Logo: assets/logo.png. A imagem foi fornecida pelo criador do catálogo.

O source.json é JSON válido, mas os apps ainda não estão publicados porque faltam dados técnicos verificáveis de cada IPA: CFBundleIdentifier, CFBundleShortVersionString, CFBundleVersion, tamanho em bytes e ícone público. Não invente esses valores.

Os cinco links estão guardados em apps-pendentes.json. O link do Octane Revival é uma página do Drive e precisa ser convertido em link de download direto verificável, além de revisão de segurança.

1. Crie um repositório público GameVault no GitHub.
2. Envie source.json e a pasta assets/ com logo.png.
3. Troque SEU-USUARIO pelo usuário real no iconURL do source.json.
4. Para cada IPA, leia Payload/*.app/Info.plist para obter CFBundleIdentifier, CFBundleShortVersionString e CFBundleVersion. Obtenha tamanho real do IPA em bytes, data real da versão, e ícone HTTPS público.
5. Adicione os objetos apps com versions conforme https://faq.altstore.io/developers/make-a-source .
6. Adicione no SideStore: https://raw.githubusercontent.com/SEU-USUARIO/GameVault/main/source.json

Observação: a imagem não parece conter conteúdo proibido ou polêmico; lembra um controle em símbolo mecânico.
