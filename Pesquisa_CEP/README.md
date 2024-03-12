# Documentação da API de Pesquisa de CEP

## Introdução

Esta API foi desenvolvida como parte do projeto da disciplina "Frameworks Para Desenvolvimento de Software" da faculdade. Ela permite a consulta de informações de endereços a partir de um CEP fornecido pelo usuário.

## Funcionalidades

- Consulta de endereço a partir do CEP
- Exibição do logradouro, bairro, cidade e UF correspondentes ao CEP consultado

## Tecnologias Utilizadas

- HTML
- CSS (Bootstrap 4.1.3)
- JavaScript

## Funcionamento

O usuário insere um CEP no campo de busca da página e, ao sair desse campo, é acionada a função `getbuscarCep(cep)`. Essa função realiza uma requisição HTTP GET para a API do ViaCEP (https://viacep.com.br/) com o CEP fornecido.

Após receber a resposta da API, os dados são convertidos para um objeto JSON, e as informações de logradouro, bairro, cidade e UF são exibidas nos campos correspondentes na página.

## Exemplo de Uso

```html
<input type="text" class="form-control" placeholder="CEP" onblur="getbuscarCep(this.value)" />
```

## Desenvolvimento

Desenvolvido por [Benetesla](https://github.com/benetesla), este projeto utiliza o framework Bootstrap para estilização e a biblioteca XMLHttpRequest para comunicação com a API do ViaCEP.

## Considerações Finais

Esta API foi criada como parte do estudo de frameworks para desenvolvimento de software e tem como objetivo demonstrar o uso de tecnologias front-end para interação com APIs de terceiros.

Para mais informações, consulte o código-fonte disponível em [GitHub - API de Pesquisa de CEP](https://github.com/benetesla/api-pesquisa-cep).

---

Espero que essa documentação atenda às suas expectativas!