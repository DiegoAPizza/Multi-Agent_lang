# Multi-Agent_lang

# 🧠 Multi-Agent Research Assistant con LangGraph

[![LangChain](https://img.shields.io/badge/LangChain-0.2.0-blue.svg)](https://python.langchain.com/)
[![LangGraph](https://img.shields.io/badge/LangGraph-0.1.0-green.svg)](https://langchain-ai.github.io/langgraph/)
[![Groq](https://img.shields.io/badge/Groq-llama--3.3--70b-orange.svg)](https://groq.com/)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

Sistema multi-agente que investiga preguntas complejas mediante la orquestación de 3 agentes especializados, con capacidad de búsqueda web en tiempo real y generación de informes estructurados.

## 🎯 ¿Qué hace?

Le haces una pregunta y el sistema:
1. 🔍 **Busca** información en la web (DuckDuckGo)
2. ⚖️ **Evalúa** si la información es suficiente
3. 🔄 **Vuelve a buscar** si es necesario (loop inteligente)
4. 📝 **Genera** un informe estructurado con fuentes

## 🏗️ Arquitectura


### Agentes

| Agente | Función | Tecnología |
|--------|---------|------------|
| **Buscador** | Búsqueda web | DuckDuckGo + Groq |
| **Crítico** | Evalúa suficiencia | Prompt + Groq (sin herramientas externas) |
| **Redactor** | Genera informe estructurado | Prompt + Groq |

## 🚀 Tecnologías utilizadas

- **LangChain** - Framework para aplicaciones LLM
- **LangGraph** - Orquestación multi-agente con estado compartido
- **Groq** - LLM gratuito (llama-3.3-70b-versatile)
- **DuckDuckGo** - Búsqueda web sin API key
- **Python 3.11+** - Lenguaje principal

## 📦 Instalación

### 1. Clonar el repositorio

```bash
git clone https://github.com/DiegoAPizza/Multi-Agent_lang.git
cd Multi-Agent_lang
