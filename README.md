Laboratório de Simulação APT - Metodologia Cyber Kill Chain
Este repositório contém os arquivos de configuração, scripts de teste e as regras personalizadas do Suricata IDS desenvolvidos para o Trabalho de Conclusão de Curso (TCC) de Bacharelado em Ciências Exatas e Tecnológicas da Universidade Federal do Recôncavo da Bahia (UFRB)
.
📌 Sobre o Projeto
O objetivo deste trabalho é avaliar a efetividade da metodologia Cyber Kill Chain na detecção de Ataques Avançados Persistentes (APT)
. O projeto utiliza um ambiente laboratorial virtualizado e segmentado para emular o ciclo de vida de uma intrusão corporativa, desde o reconhecimento inicial até a movimentação lateral (pivoting)
.
📂 Conteúdo do Repositório
suricata.rules: Conjunto de regras customizadas para a detecção de varreduras furtivas (Nmap), exploração de serviços (FTP) e assinaturas de exploits conhecidos (EternalBlue)
.
Scripts de Automação: Scripts em Python desenvolvidos para auxiliar nos testes de estresse de rede e simulação de anomalias volumétricas
.
Documentação da Topologia: Detalhes da arquitetura de rede interligando os nós Debian (Atacante e Defesa), Metasploitable (Linux) e Metasploitable3 (Windows)
.
🛠️ Tecnologias Utilizadas
Hipervisor: Oracle VirtualBox
.
IDS: Suricata
.
Análise de Tráfego: Wireshark
.
Ferramentas Ofensivas: Nmap e Metasploit Framework
.
🚀 Como Utilizar
As regras contidas no arquivo .rules devem ser importadas para o diretório de assinaturas do seu Suricata IDS para replicar os alertas quantitativos demonstrados nos resultados do trabalho (como os alertas das fases de Reconhecimento e Exploração)
.
🎓 Autor
Braian de Jesus Pinto
Orientador: Prof. Dr. Tassio Valle
.
Dica do guia: Ao criar o arquivo no GitHub:
Clique em "Add file" > "Create new file".
Dê o nome de README.md.
Cole o texto acima.
Certifique-se de que o arquivo de regras que você vai subir tenha o mesmo nome citado no texto (ex: suricata.rules).
