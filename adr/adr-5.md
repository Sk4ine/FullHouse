# ADR-5 Безопасность

### Hashicorp Vault:
**Обоснование**:
- Автоматическая смена JWT-ключей каждые 24ч
- Policy-based доступ к партнерским API-ключам

### OWASP ZAP:
**Обоснование**:
- Автоматическое сканирование на:
  - SQL-инъекции
  - Небезопасные десериализации
  - Broken Authentication