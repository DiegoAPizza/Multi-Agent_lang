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
