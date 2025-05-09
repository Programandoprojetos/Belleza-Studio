# Bellezza Studio - Agendamento de Serviços

Este projeto é um sistema simples de agendamento de serviços para um estúdio de beleza, onde os usuários podem agendar, cancelar ou remarcar horários. Além disso, ele oferece uma interface para os administradores gerenciarem os agendamentos.

## Funcionalidades

### Para Usuários
- **Agendamento de Serviços:** O usuário pode escolher o serviço desejado, selecionar a data e o horário, e fornecer as informações necessárias para finalizar o agendamento.
- **Notificações de Agendamentos:** O sistema notifica os usuários sobre agendamentos confirmados para o dia atual ou o próximo.
- **Serviços Oferecidos:** O estúdio oferece uma variedade de serviços como manicure, pedicure, alongamento de unhas, cabeleireiro, entre outros.

### Para Administradores
- **Login de Administrador:** Administradores podem acessar um painel de controle para gerenciar os agendamentos.
- **Tabela de Agendamentos:** Administradores podem visualizar todos os agendamentos feitos, com a opção de confirmar, cancelar ou remarcar os agendamentos.
- **Edição e Exclusão:** O administrador pode alterar o status dos agendamentos e excluir aqueles que não forem mais necessários.
- **Controle de Ações:** Existem botões para remarcar ou excluir agendamentos diretamente da tabela de agendamentos.

## Estrutura de Diretórios

/static
       /images
              logo.png
/index.html

### Arquivos Principais

1. **index.html**: Contém o código HTML e JavaScript que implementa as funcionalidades do agendamento.
2. **/static/images/logo.png**: Imagem do logo do estúdio Bellezza Studio.

## Dependências

- **HTML5**: Estrutura de marcação da página.
- **CSS3**: Estilos para responsividade e personalização da interface.
- **JavaScript**: Funções para interação dinâmica, como agendamento e login de administradores.

## Funcionalidades Específicas

- **Formulário de Agendamento**: A interface permite que o cliente insira seu nome e número de telefone ao fazer um agendamento.
- **Login de Administrador**: Admins podem fazer login para desbloquear funcionalidades de gestão de agendamentos.
- **Interatividade Dinâmica**: O JavaScript gerencia a seleção de horários, a atualização da tabela de agendamentos, e a visualização de notificações.
  
## Como Usar

### 1. Iniciar o Agendamento
- O usuário deve preencher o formulário com seu nome, telefone, escolher um serviço, selecionar a data e escolher o horário.
  
### 2. Login de Administrador
- Para acessar o painel de controle do administrador, faça login com o nome de usuário **admin** e senha **admin123**.

### 3. Gerenciamento de Agendamentos
- Após o login, o administrador pode visualizar todos os agendamentos e realizar ações como confirmar, cancelar ou remarcar.
  
## Tecnologias Utilizadas
- **HTML**: Estrutura da página e formulários de interação.
- **CSS**: Estilos e layout responsivo para diferentes dispositivos.
- **JavaScript**: Funcionalidades dinâmicas, como login, gerenciamento de agendamentos, e controle de UI.

## Responsividade

O sistema foi projetado para ser responsivo, ajustando-se a diferentes tamanhos de tela, como em dispositivos móveis e desktops.

## Contribuições

Este projeto é open-source e aceita contribuições para melhorias, como novos serviços, funcionalidades adicionais e correção de bugs.

## Licença

Este projeto está licenciado sob a [Licença MIT](LICENSE).

---

**Criador:** Programando Projetos