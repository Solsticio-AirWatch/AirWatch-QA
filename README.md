# AirWatch-QA

Documentação de arquitetura empresarial do projeto AirWatch no padrão TOGAF/ArchiMate.

## Sobre

O AirWatch é uma plataforma de monitoramento de qualidade do ar que combina dados satelitais (Sentinel-5P, OpenAQ, Open-Meteo) com um sensor IoT local (ESP32). Este repositório contém a documentação de arquitetura seguindo o framework TOGAF, modelada com a notação ArchiMate.

## Estrutura
```
archimate/
├── airwatch_QA.archimate   # arquivo fonte — abrir com Archi
└── QA_GS.pdf               # export visual do diagrama
README.md
```

## Camadas documentadas

- **Motivação** — stakeholders, drivers e objetivos (ODS 3, 11 e 13)
- **Negócio** — processos de cadastro, coleta, avaliação e alerta
- **Aplicação** — API Java, API .NET, Dashboard web, Firmware ESP32
- **Tecnologia** — Railway, Oracle Cloud, HiveMQ, ESP32/Wokwi, Sentinel-5P

## Integrantes

| Nome | RM |
|---|---|
| Felipe Modesto | 561810 |
| Enrico Delesporte | 565760 |
| Vitor Dias dos Santos | 565422 |

**Curso:** Análise e Desenvolvimento de Sistemas — 2TDS Fevereiro  
**FIAP — Global Solution 2026/1**
