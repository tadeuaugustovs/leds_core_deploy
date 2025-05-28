# LEDS Core – Deploy Automático com Docker

Sistema completo com backend Strapi, frontend Appsmith e banco PostgreSQL.

---

## 🧩 Requisitos

- Docker + Docker Compose
- pgAdmin (para restaurar o banco de dados)
- Backup: `leds_core.backup`

---

## 🚀 Como rodar

1. **Restaurar o banco de dados:**

   - Abra o pgAdmin
   - Crie um banco chamado `leds_core`
   - Clique com o botão direito no banco → Restore...
   - Escolha o arquivo `leds_core.backup`

2. **Subir o sistema:**

```bash
docker compose up -d
