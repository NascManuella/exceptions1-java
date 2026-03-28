# 🏨 Reservation System (Java)

Projeto desenvolvido em Java com foco em **Programação Orientada a Objetos** e **tratamento de exceções personalizadas**.

---

## 📌 Sobre o projeto

Este sistema simula o gerenciamento de reservas de um hotel via terminal, permitindo:

* Criar uma reserva com número do quarto
* Definir datas de check-in e check-out
* Atualizar as datas da reserva
* Validar regras de negócio
* Tratar erros de forma elegante com exceções personalizadas

---

## 🧠 Conceitos aplicados

* Programação Orientada a Objetos (POO)
* Encapsulamento
* Tratamento de exceções (`try/catch`)
* Exceções personalizadas
* Manipulação de datas (`Date`, `SimpleDateFormat`)
* Boas práticas de validação de regras de negócio

---

## ⚙️ Regras de negócio

O sistema valida:

* ❌ Check-out deve ser após o check-in
* ❌ Datas de atualização devem ser futuras
* ❌ Formato de data inválido é tratado

---

## 🧩 Estrutura do projeto

```
src/
├── application/
│   └── Program.java
├── model/
│   ├── entities/
│   │   └── Reservation.java
│   └── exceptions/
│       └── DomainException.java
```

---

## 🚀 Como executar

1. Clone o repositório:

```
git clone https://github.com/NascManuella/exceptions1-java.git
```

2. Abra no Eclipse ou qualquer IDE Java

3. Execute a classe:

```
application.Program
```

---

## 💻 Exemplo de uso

```
Room number: 101
Check-in date (dd/MM/yyyy): 20/04/2026
Check-out date (dd/MM/yyyy): 25/04/2026

Reservation: Room 101, check-in: 20/04/2026, check-out: 25/04/2026, 5 nights
```

---

## ⚠️ Tratamento de erros

O sistema utiliza uma exceção personalizada:

`DomainException`

Exemplos de erros tratados:

* Datas inválidas
* Datas no passado
* Check-out antes do check-in

---

## ⭐ Objetivo

Este projeto foi desenvolvido com fins educacionais para reforçar conceitos fundamentais de Java e preparar para aplicações reais no mercado.

---
