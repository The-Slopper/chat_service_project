# cpp-chat

Servidor de mensagens em C++. Armazena mensagens, busca por autor e mantém
contadores de uso.

## Compilando

```bash
g++ -std=c++17 -O2 -o chat chat.cpp
./chat
```

## Componentes

- `MessageStore` — persistência e busca de mensagens
- `find_recent` — retorna ponteiro para a última mensagem de um autor
- `count_words` — estatística de palavras
