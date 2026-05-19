# Projeto Integrador - Baby corporation

Um modelo para o desenvolvimento do Projeto Integrador do Curso de Técnico em Desenvolvimento de Sistemas para a Internet Integrado ao Ensino Médio do IFC - Campus Araquari.
*(Em nosso site pode-se achar serviços de babás e seu curriculo logo abaixo.)*

**IMPORTANTE**: [**Cadastre seu projeto nesta planilha**](https://docs.google.com/spreadsheets/d/1bSb1-S9qOf46fNH8quyoFpcjcTuBMj_EdSPchOuFULY/edit?usp=sharing).

Professor: [Marco André Mendes](github.com/marcoandre)

Equipe:
- [Pedro Gabriel Vieira](https://github.com/pedropg22)
- [Daniel Henrique Fernades ](https://github.com/danielhenrique090109)
- [Lucidrey Valentina Maita Bonilla](https://github.com/Lucidrey).

Links do projeto:
(*https://github.com/babys-corporation*)
-   Documentação (esse documento)](github.com/marcoandre/pi-modelo)
-   Backend: [Repositório](github.com/marcoandre/pi-backend) e [Publicação](https://pi-backend.herokuapp.com/)
-   Frontend: [Repositório](github.com/marcoandre/pi-frontend) e [Publicação](https://pi-frontend.herokuapp.com/)

# 2. Situação Problema

A “Babyscorporation” é uma rede de babás que conecta famílias e profissionais, mas atualmente funciona de forma manual, usando principalmente Whatsapp e planilhas. O agendamento é demorado, porque depende de confirmar disponibilidade individualmente com cada babá, podendo gerar conflitos de horário.

As informações das profissionais são desorganizadas, dificultando a escolha da mais adequada. Além disso, não há controle eficiente dos pagamentos, nem um sistema estruturado de avaliações. A comunicação é dispersa e sujeita a erros.

Esses problemas mostram a necessidade de um sistema que organize e automatize os processos da empresa.

# 3. Descrição da proposta

O software proposto terá como foco centralizar e automatizar o gerenciamento da rede de babás. Ele permitirá controlar agendas, cadastrar profissionais, organizar informações, registrar avaliações e acompanhar pagamentos.

Haverá dois tipos de usuários: o administrador, com acesso completo, as babás, que poderão gerenciar sua disponibilidade e atendimentos e os clientes, que poderam requisitar os serviços da empresa.

Com isso, a empresa ganhará mais organização, agilidade e qualidade no serviço prestado.

# 4. Modelagem de Dados
<img width="727" height="548" alt="WhatsApp Image 2026-04-24 at 12 59 57" src="https://github.com/user-attachments/assets/87b3d931-ec23-43c6-8b04-d87521ab2b63" />

# 4. Regras de negócio
*(Aqui vocês devem listar as Regras de Negócio específicas da Babyscorporation, ex: RN01 - Cadastro de Babá: A profissional só pode se cadastrar se informar um CPF válido e telefone.)*

# 5. Requisitos funcionais
RF001: ao entar no site o usuario deve ver uma parte introdutoria onde em seu final tera a opção de logar como responsavel ou baba

RF002: se o usuario escolher baba ele deve logar com essas informações: Nome da babá ,Data de nascimento,Experiência,Preço,Educação,Dias disponiveis,Habilidades,Sobre você,CPF,Número de telefone, Endereço ,Alergias, Condições medicas

RF003: se o usuario logar como pais ele deve cadastrar pais com essas informações: Nome de responsavel,CPF,Número de telefone,Endereço

RF004: o usuario que estiver logando como pai deve tambem cadastar seus filhos com as seguintes informações para cada filho: Nome da criança,Genero,Idade,Alergias,Condições fisicas/mentais

RF005: se o usuario tiver logado como baba ela deve iniar numa tela onde vera seus medidos os rrspondera.

RF006: o usuario tipo baba deve ter uma segunda area onde pode ver seu perfil e la adicionar sua foto

RF007: se o usuario logar como pai ele deve iniciar em uma parte onde ele ve as opçoes de babas la tendo um resumo de suas informações e suas fotos

RF008: o site deve ter uma filtragem de nomes localizações e abilidades das babas

RF009: se o usuario tipo pai clicar em um perfil de uma baba , deve-se caregar uma pagina da baba e suas informações onde abaixo avera um calendario com seus dias disponiveis e um botão de atendimento

RF010: o site deve abrir uma pagina de agendamentos ao clicar em agendamentos na pagina baba do usuario

RF011: a pagina de agendamentos onde dele a informação do preso sua disponibilidade e abaixo um botão de pgamento que levara a sua chave pix

# 6. Requisitos não funcionais

RNF001: o site deve ser feito em cores pasteis
RNF002: o frontend deve ser feito em vue.js
RNF003: o backend deve ser feito com python django
