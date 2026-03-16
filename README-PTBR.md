# Laboratório SOC — SIEM com Splunk

Este projeto documenta a implementação de um pequeno laboratório de SOC utilizando Splunk.

O laboratório simula um pipeline de monitoramento onde:

Kali Linux - gera atividade de ataque  
Windows - registra eventos de segurança  
Splunk - coleta e analisa os logs

## Arquitetura

- Kali Linux — máquina atacante
- Windows — endpoint monitorado
- Ubuntu Server — SIEM com Splunk

## Tecnologias Utilizadas (até então)

- Splunk Enterprise
- Splunk Universal Forwarder
- Windows Event Logs
- Ubuntu Server
- Kali Linux

## Próximas Etapas

- telemetria avançada com Sysmon
- cenários de simulação de ataques
- criação de detecções utilizando SPL
- criação de dashboards de segurança
