O **Amazon EC2** (*Elastic Compute Cloud*) é um serviço da **AWS** que permite criar e gerenciar servidores virtuais (chamados de **instâncias**) na nuvem.

---

## Em detalhes

- **Compute** → capacidade de processamento, ou seja, rodar aplicações, sites, sistemas, etc.  
- **Cloud** → hospedado nos data centers da AWS, sem necessidade de comprar ou configurar servidores físicos.  
- **Elastic** → possibilidade de aumentar ou diminuir a quantidade de servidores conforme a necessidade, pagando somente pelo que usar.

---

## Para que serve o EC2?

- Hospedar sites e aplicações web.
- Rodar banco de dados, sistemas internos, APIs, etc.
- Processar grandes volumes de dados (*Big Data*, *Machine Learning*).
- Servir como servidor de arquivos, aplicações empresariais e muito mais.

---

## Como funciona na prática?

1. Escolha uma configuração (ex.: quantidade de CPU, memória, sistema operacional: **Linux** ou **Windows**).
2. Lance uma instância (um servidor virtual).
3. Acesse remotamente via **SSH** (Linux) ou **RDP** (Windows).
4. Instale e rode o que quiser, como se fosse um computador próprio.

---

## Benefícios principais

- **Escalabilidade** → Crie e remova instâncias rapidamente.
- **Custo sob demanda** → Pague somente pelo tempo de uso.
- **Flexibilidade** → Diversos tipos de máquinas, sistemas operacionais e configurações.
- **Segurança** → Controle de acesso com **IAM**, firewalls (*Security Groups*), etc.

---

## Exemplo prático

Imagine que você precise de um servidor para rodar um site por alguns meses. Com o EC2, você:

1. Cria uma instância.
2. Instala o servidor web (como **Apache** ou **Nginx**).
3. Sobe seu site.
4. Quando não precisar mais, desliga e para de pagar.
