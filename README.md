# Projeto React - Loja Virtual

Loja de jogos com as págias Home, Loja e Contato.

Desenvolvido com React e o componente react-router-dom que é utilizado para permitir a troca de páginas.

## Como rodar o projeto

Abra o terminar do PowerShell e execute o comando abaixo:

```bash
npm start
```

Acessar a aplicação em http://localhost:3000.


## Estrutura do projeto

As pastas estão organizadas da seguinte forma:

Componentes do projeto:

- \Components
  - Header.js = Cabeçalho da página
  - Footer = Rodapé da página

- \CSSdaPageCompra = Arquivo CSS de cada um dos jogos

- \CSSdeCadaPagina
  - header.css

- \imgsCds = Imagem dos CD's

- \imgsJogos = Imagem do banner dos jogos

- \imgsParceria =  Imagem do logo das empresas


- \pageComprarJogo = Página de compra


 - \Variaveis = Variáveis dos textos


## Atualização

No site está sendo utilizado variáveis para permitir atualizar os conteúdos.

Por exemplo para alterar o valor do jogo Elder, precisamos:

1- Alterar o valor no arquivo: `variaveisPrecosJogs.js`

```
export const preçoEldenRing = 'R$:275,84'
```

e o valor será automaticamente exibido na página de compra, devido ao código abaixo no arquivo `Loja.js`:

  import precoJogo from '../Variaveis/variavesiPrecosJogs.js'

     <div>
        <p>
            {precoJogo}
        </p>
      </di>


## Como criar um projeto igual

Criar o projeto

```bash
npx create-react-app loja
```

Adicionar o componente react-router-dom

```bash
npm install react-router-dom
```



<img width="1908" height="898" alt="Image" src="https://github.com/user-attachments/assets/8ea377d7-0425-4cf2-9793-de988b51965c" />

<img width="1885" height="719" alt="Image" src="https://github.com/user-attachments/assets/c00f65c4-650d-470d-9c64-b6aaeb2de4fe" />

<img width="1883" height="650" alt="Image" src="https://github.com/user-attachments/assets/e822c714-d12d-4811-8c3b-ea0ad5e7f087" />

<img width="1906" height="886" alt="Image" src="https://github.com/user-attachments/assets/b92f302c-2a5e-4ef8-a499-e7ec44b674ff" />

<img width="1890" height="249" alt="Image" src="https://github.com/user-attachments/assets/71507729-b533-49d6-a9cc-d688fc58c37a" />
