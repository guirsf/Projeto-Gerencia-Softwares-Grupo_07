# Projeto-Gerencia-Softwares-Grupo_07
Projeto de planejamento da implantação de um sistema ERP em uma empresa
# 🖨️ Implantação de Sistema ERP – Novaprint

📚 Projeto Acadêmico  
🎓 Curso: Tecnologia da Informação  

---

## 🏢 Sobre a Empresa

**Nome:** Novaprint  
**Segmento:** Serviços gráficos e comunicação visual  
**Porte:** Pequena empresa  
**Funcionários:** 7  
**Usuários do ERP:** 5  
**Tipo de negócio:** Prestação de serviços gráficos  

---

## 🏗️ Estrutura Organizacional

| Código | Departamento     | Responsabilidade                          |
|--------|----------------|------------------------------------------|
| DEP01  | Comercial       | Vendas e relacionamento com clientes     |
| DEP02  | Marketing       | Criação de artes gráficas                |
| DEP03  | Financeiro      | Contas a pagar e receber                |
| DEP04  | Compras         | Contratação de serviços terceirizados    |
| DEP05  | Administrativo  | Apoio operacional                        |
| DEP06  | Recepção        | Atendimento inicial ao cliente           |

---

## 👥 Funcionários

| ID     | Cargo                     | Departamento     | Salário   |
|--------|--------------------------|------------------|----------|
| FUNC01 | Vendedor                 | Comercial        | R$ 2.500 |
| FUNC02 | Designer                 | Marketing        | R$ 2.100 |
| FUNC03 | Analista Financeiro      | Financeiro       | R$ 2.900 |
| FUNC04 | Comprador                | Compras          | R$ 2.349 |
| FUNC05 | Auxiliar Administrativo  | Administrativo   | R$ 2.000 |
| FUNC06 | Auxiliar Administrativo  | Administrativo   | R$ 2.000 |
| FUNC07 | Recepcionista            | Recepção         | R$ 2.000 |

---

## 🛠️ Serviços Oferecidos

| Código | Serviço             | Categoria              |
|--------|--------------------|------------------------|
| SRV01  | Adesivação         | Comunicação visual     |
| SRV02  | Cartão de visita   | Impressão              |
| SRV03  | Panfleto           | Impressão              |
| SRV04  | Criação de arte    | Design                 |

---

## 💰 Tabela de Preços

### 🧾 Adesivação
| Código | Descrição                 | Preço        |
|--------|--------------------------|-------------|
| AD001  | Preto e Branco           | R$ 49,90/m² |
| AD002  | Colorido                 | R$ 69,90/m² |

### 📇 Cartão de Visita
| Código | Quantidade | Preço  |
|--------|-----------|--------|
| CV001  | 1000      | R$ 200 |
| CV002  | 3000      | R$ 350 |
| CV003  | 5000      | R$ 500 |

### 📄 Panfletos
| Código | Quantidade | Preço  |
|--------|-----------|--------|
| PF001  | 1000      | R$ 180 |
| PF002  | 3000      | R$ 280 |
| PF003  | 5000      | R$ 365 |

### 🎨 Criação de Arte
| Código | Serviço              | Preço |
|--------|----------------------|------|
| ART01  | Arte gráfica         | R$ 50 |

---

## 🤝 Fornecedores

| Código | Serviço                          | Tipo       |
|--------|----------------------------------|------------|
| FOR01  | Impressão terceirizada           | Produção   |
| FOR02  | Comunicação visual terceirizada  | Produção   |

---

## 📉 Custos de Produção

### Adesivos
| Tipo            | Custo        |
|-----------------|-------------|
| Preto e branco  | R$ 29,90/m² |
| Colorido        | R$ 39,90/m² |

### Cartões de Visita
| Quantidade | Custo  |
|-----------|--------|
| 1000      | R$ 100 |
| 3000      | R$ 170 |
| 5000      | R$ 300 |

### Panfletos
| Quantidade | Custo  |
|-----------|--------|
| 1000      | R$ 100 |
| 3000      | R$ 180 |
| 5000      | R$ 260 |

---

## 💸 Custos Fixos

| Código | Despesa  | Valor            |
|--------|----------|------------------|
| CF001  | Aluguel  | R$ 1.890         |
| CF002  | Água     | R$ 300 a R$ 400  |
| CF003  | Energia  | R$ 250 a R$ 500  |

---

## 🔄 Processos de Negócio

```mermaid
graph TD
A[Cliente solicita orçamento] --> B[Recepção registra pedido]
B --> C[Comercial valida orçamento]
C --> D[Marketing cria arte]
D --> E[Compras verifica terceirização]
E --> F[Produção / Fornecedor executa]
F --> G[Financeiro gera cobrança]
G --> H[Entrega ao cliente]
