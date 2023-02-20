- #### SSH KEY (USAR GIT BASH)
	- **ssh-keygen -t ed25519 -C** [*e-mail da sua conta*]
	> vai gerar a chave privada e a chave publica
	> copiar a chave publica e configurar dentro do GitHub
	- **eval $(ssh-agent -s)**
    > inicia o serviço de ssh
	- **ssh-add** [*nome arquivo chave privada*]
    > adiciona a chave privada no serviço de SSH
	- **git clone** (URL SSH)
	> Para clonar um repositório agora pode usar a URL do SSH

- #### TOKEN DE ACESSO
	- Settings / Developper settings / Personal access tokens
	- Botão ***Generate new token*** 
    - Salvar o token gerado em local seguro, pois não mostrará novamente
	- **git clone** (URL HTTPS)
	> vai pedir autenticação, utilize o TOKEN gerado anteriormente