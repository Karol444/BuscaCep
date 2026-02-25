BuscaCEP

Este é um aplicativo web simples que permite aos usuários buscar endereços com base no CEP brasileiro. A aplicação utiliza o serviço web ViaCEP para obter as informações de endereço.

✨ Funcionalidades

Formulário de Entrada:
Possui campos para informações do usuário (Nome, Telefone, Email) e dados de endereço (CEP, Rua, Bairro, Número, Cidade, Estado).

Consulta de CEP:
Ao inserir um CEP e sair do campo (evento blur), a aplicação realiza automaticamente uma requisição ao serviço ViaCEP.

Preenchimento Automático:
Se o CEP for válido, os campos de Rua, Bairro, Cidade e Estado são preenchidos automaticamente com os dados retornados pela API.

Tratamento de Erros:
Exibe uma mensagem de alerta caso o CEP seja inválido ou não seja encontrado na base de dados do ViaCEP.

Limpeza Automática do Formulário:
Os campos de endereço são limpos caso o CEP esteja vazio ou inválido.

📦 Dependências

jQuery (incluído via CDN)

🛠️ Tecnologias Utilizadas

HTML – Estrutura da página e do formulário

JavaScript – Manipulação do DOM, requisições AJAX e interações do usuário

jQuery – Simplificação da manipulação do DOM e requisições AJAX

ViaCEP API – Serviço web (viacep.com.br) para consulta de endereços a partir do CEP

🚀 Como Utilizar

Abra o arquivo busca-cep.html no navegador.

Preencha as informações do usuário:

Nome

Telefone (campo obrigatório, com formato sugerido)

Email

Digite o CEP no campo correspondente.

Saia do campo CEP (clicando fora ou pressionando Tab) para disparar a consulta automática.

Visualize os resultados:

Se o CEP for válido, os campos de endereço serão preenchidos automaticamente.

Se o CEP for inválido ou não encontrado, será exibido um alerta e os campos serão limpos.

Complete o campo “Número”.

Botão “Enviar”:
Atualmente não possui funcionalidade. Para que o envio funcione, seria necessário integrar a aplicação com um script back-end para processar os dados do formulário.
