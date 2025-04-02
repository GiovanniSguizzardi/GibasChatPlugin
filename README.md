![minecraft_chat](https://github.com/user-attachments/assets/92aaba25-f2a7-4dab-a33c-e3f40957ea2d)

# 🗨️ GibasChat

Um plugin de chat avançado e personalizável para servidores Minecraft, com suporte a **canais de chat** (global, local e privado), **formatação com tags** integrada ao [GibasTags](https://github.com/seu-user/GibasTags) e **recursos modernos** para comunidades roleplay, survival ou PvP.

![Minecraft](https://img.shields.io/badge/Minecraft-1.21-brightgreen)
![Feito por](https://img.shields.io/badge/Feito%20por-Giovanni-blue)
![Plugin Integrado](https://img.shields.io/badge/Integrado%20com-GibasTags-purple)

---

## ✨ Funcionalidades

✅ Tags customizadas por jogador (via GibasTags)  
✅ Chat **local** com raio configurável  
✅ Chat **global** acessível de qualquer mundo  
✅ Chat **privado** com `/tell` e `/r`  
✅ Prefixos visuais no chat: `[G]`, `[L]`, `📧`  
✅ Configuração de mensagens e estilos via `config.yml`  
✅ Comando `/gibaschat reload` para recarregar config

---

## ⚙️ Comandos

| Comando             | Descrição                                     |
|---------------------|-----------------------------------------------|
| `/g <mensagem>`     | Envia uma mensagem para todos os jogadores    |
| `texto direto`      | Envia mensagem apenas para quem está por perto |
| `/tell <jogador> <mensagem>` | Envia uma mensagem privada               |
| `/r <mensagem>`     | Responde à última mensagem privada recebida   |
| `/gibaschat reload` | Recarrega o `config.yml`                      |

---

## 📦 Instalação

1. Faça o download do `GibasChat.jar`.
2. Coloque o arquivo na pasta `plugins/` do seu servidor Minecraft.
3. Certifique-se de que o plugin **GibasTags** também esteja instalado.
4. Reinicie o servidor.

---

## 🧩 Integração com GibasTags

O plugin **GibasChat** se conecta automaticamente ao `tags.yml` do plugin **GibasTags**.

```yaml
# Exemplo de tags.yml
tags:
  98732450-b260-4968-a95f-c31a12cb08c3:
    tag: "&cAdmin"
