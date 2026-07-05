# Projeto-Django

# Demo Django

Este repositório contém o projeto desenvolvido para a disciplina de **Programação Web**, utilizando **Django**, **Docker**, **SQLite** e **Tailwind CSS**.

A branch `main` é utilizada apenas para informações gerais sobre o repositório. O código-fonte está organizado por etapas de desenvolvimento, conforme os roteiros da disciplina.

## Branches do projeto

### `bcc481-django-parte1`

Contém a implementação do primeiro roteiro do projeto, incluindo:

* Configuração inicial do ambiente com Docker;
* Criação do projeto Django;
* Configuração do banco de dados SQLite;
* Estrutura inicial da aplicação;
* Página inicial utilizando Tailwind CSS via CDN.

#### Capturas de tela

**Página inicial**

<p align="center">
  <img width="1836" height="1034" alt="Screenshot from 2026-06-28 17-32-30" src="https://github.com/user-attachments/assets/e7ad2900-9b44-46a1-9ae8-9b3bfd9a1be5" alt="Página inicial" width="800"/>

</p>

---

### `bcc481-django-parte2`

Contém a continuação do projeto, implementando todas as atividades propostas no segundo roteiro:

* Cadastro e gerenciamento de mensagens pelo painel administrativo do Django;
* Criação de usuário administrador (`createsuperuser`);
* Exibição das mensagens cadastradas na página inicial;
* Inclusão do campo **autor** no modelo `Mensagem`;
* Geração e aplicação de migrations;
* Criação da página **Sobre** (`/sobre/`);
* Configuração de novas rotas e views;
* Navegação entre as páginas da aplicação;
* Personalização do layout utilizando Tailwind CSS;
* Organização da aplicação seguindo o padrão **MTV (Model–Template–View)** do Django.

#### Capturas de tela

**Página inicial com mensagens**

<p align="center">
  <img width="1836" height="1034" alt="Screenshot from 2026-06-28 17-50-24" src="https://github.com/user-attachments/assets/21356a02-402e-4f0f-8ae8-14b3422282c1" alt="Página inicial com mensagens" width="800"/>
</p>

**Painel administrativo**

<p align="center">
  <img width="1836" height="1034" alt="Screenshot from 2026-06-28 17-48-37" src="https://github.com/user-attachments/assets/1ca5acd5-9e51-44dc-bb73-fc4973fb1039"  alt="Painel administrativo" width="800"/>
</p>

**Mensagem com Campo Autor e Rota Sobre no Topo da Site**

<p align="center">
  <img width="1836" height="1034" alt="Screenshot from 2026-06-28 18-01-38" src="https://github.com/user-attachments/assets/8f0cae47-9dda-4035-b5b2-0f7d2a159b52" alt="Mensagem com Campo Autor e Rota Sobre no Topo da Site" width="800"/>
</p>


---

### `bcc481-django-parte3`

Contém a implementação do terceiro roteiro, adicionando relacionamento entre modelos e expandindo as funcionalidades da aplicação.

Nesta etapa foram implementados:

* Criação do modelo **Categoria**;
* Relacionamento **um-para-muitos (1:N)** entre `Categoria` e `Mensagem` utilizando `ForeignKey`;
* Configuração da política de exclusão com `on_delete=models.SET_NULL`;
* Registro do modelo `Categoria` no painel administrativo do Django;
* Inclusão da categoria na listagem do painel administrativo;
* Adição de filtros e pesquisa por categoria no Admin;
* Geração e aplicação das novas migrations;
* Cadastro de categorias pelo painel administrativo;
* Associação de mensagens às respectivas categorias;
* Exibição da categoria na página inicial utilizando um selo (badge) estilizado com Tailwind CSS;
* Continuidade da organização do projeto seguindo o padrão **MTV (Model–Template–View)** do Django.

#### Capturas de tela

**Página do admin com Mensagem e Categorias**

<p align="center">
  <img width="1846" height="1041" alt="Screenshot from 2026-07-05 20-26-36" src="https://github.com/user-attachments/assets/5f8fc032-7810-4b7b-babd-ac3e5aea3ca8" alt="Página do admin com Mensagem e Categorias*<img width="1846" height="1041" alt="Screenshot from 2026-07-05 20-26-45" src="https://github.com/user-attachments/assets/44b81105-f717-45bd-b632-291bd91c394a" />
" width="800"/>
</p>

**Categoria Aviso Cadastrada**

<p align="center">
  
<img width="1846" height="1041" alt="Screenshot from 2026-07-05 20-26-45" src="https://github.com/user-attachments/assets/58aaad93-997f-4da3-a44a-b0864af34bcc" alt="Categoria Aviso Cadastrada" width="800"/>
</p>

**Página Inicial com Mensagens e Categorias**

<p align="center">
  <img width="1846" height="1041" alt="Screenshot from 2026-07-05 20-28-23" src="https://github.com/user-attachments/assets/d44a4735-62f3-46b7-902d-434d5ecdba89" alt="Lista de mensagens com categorias" width="800"/>
</p>


---

## Como acessar cada etapa

Clone o repositório:

```bash
git clone <URL_DO_REPOSITORIO>
cd demo-django
```

Para acessar a primeira parte:

```bash
git checkout bcc481-django-parte1
```

Para acessar a segunda parte:

```bash
git checkout bcc481-django-parte2
```

Para acessar a terceira parte:

```bash
git checkout bcc481-django-parte3
```

Cada branch representa um marco do desenvolvimento do projeto e corresponde ao respectivo roteiro da disciplina.
