# 🧠 SQL Agent con LangChain (Chinook DB)

Este proyecto implementa un **SQL Agent utilizando LangChain** capaz de responder preguntas en lenguaje natural sobre una base de datos relacional (Chinook).

El objetivo es demostrar cómo los LLMs pueden interactuar con bases de datos estructuradas para generar insights sin necesidad de escribir SQL manualmente.

---

## 🚀 Features

- Conversión de lenguaje natural → SQL
- Ejecución automática de queries
- Respuestas interpretadas por LLM
- Uso de LangChain Agents
- Integración con base de datos Chinook (SQLite)

---

## 🧱 Tech Stack

- Python
- LangChain
- SQLAlchemy
- SQLite (Chinook DB)
- OpenAI / Gemini (LLM)

---

## 📊 Ejemplos de preguntas

Puedes hacer preguntas como:

- "¿Cuáles son los 5 artistas con más ventas?"
- "¿Qué género genera más ingresos?"
- "¿Cuántos clientes hay por país?"
- "Top 10 canciones más vendidas"

---

## ⚙️ Instalación

1. Clona el repositorio:

```bash
git clone https://github.com/cesarahernandez17-dotcom/sql-agent-chinook-langchain.git
cd sql-agent-chinook-langchain

pip install -r requirements.txt

cp .env.example .env
