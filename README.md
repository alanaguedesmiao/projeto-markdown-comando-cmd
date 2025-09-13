# 📟 Comandos do CMD para Usos Técnicos

Este documento lista comandos básicos e técnicos do Prompt de Comando (CMD) do Windows, úteis para suporte, manutenção e automação de tarefas.

---

## 🗂️ Navegação entre Pastas

| Comando | Descrição |
|--------|------------|
| `cd` | Mostra o diretório atual |
| `cd nome_da_pasta` | Acessa a pasta desejada |
| `cd ..` | Volta uma pasta |
| `dir` | Lista arquivos e diretórios |
| `cls` | Limpa a tela do terminal |

---

## 📁 Gerenciamento de Arquivos e Pastas

| Comando | Descrição |
|--------|-----------|
| `mkdir nome_da_pasta` | Cria uma nova pasta |
| `rmdir nome_da_pasta` | Remove uma pasta vazia |
| `rmdir /s nome_da_pasta` | Remove a pasta e tudo dentro dela |
| `del arquivo.txt` | Apaga um arquivo |
| `copy origem destino` | Copia arquivos |
| `move origem destino` | Move ou renomeia arquivos |
| `rename antigo.txt novo.txt` | Renomeia um arquivo |

---

## 🧠 Diagnóstico e Informações do Sistema

| Comando | Descrição |
|--------|-----------|
| `systeminfo` | Informações detalhadas do sistema |
| `ver` | Mostra a versão do Windows |
| `hostname` | Nome do computador |
| `tasklist` | Lista processos em execução |
| `taskkill /im nome.exe /f` | Finaliza um processo |
| `sfc /scannow` | Verifica arquivos corrompidos do sistema |
| `chkdsk /f` | Verifica e corrige erros no disco |

---

## 🌐 Comandos de Rede

| Comando | Descrição |
|--------|-----------|
| `ipconfig` | Mostra configurações de IP |
| `ipconfig /release` | Libera o IP atual |
| `ipconfig /renew` | Solicita novo IP |
| `ping endereço` | Testa conectividade com um host |
| `tracert endereço` | Rastreia a rota até um host |
| `netstat -an` | Mostra conexões de rede e portas abertas |
| `nslookup site.com` | Consulta DNS de um domínio |

---

## 🧰 Utilitários e Dicas

- `echo texto` → Exibe uma mensagem
- `exit` → Fecha o CMD
- `comando /?` → Mostra ajuda sobre o comando

---

## 📌 Exemplo Prático

```cmd
ping google.com
ipconfig /all
taskkill /im chrome.exe /f

















































