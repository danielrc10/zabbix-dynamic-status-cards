# Cards de status dinâmicos / Dynamic Status Cards

[![Validate module](https://github.com/danielrc10/zabbix-dynamic-status-cards/actions/workflows/validate.yml/badge.svg)](https://github.com/danielrc10/zabbix-dynamic-status-cards/actions/workflows/validate.yml)

[Português](#português) · [English](#english)

## Português

Módulo independente para criar cards de status genéricos em dashboards do Zabbix. Cada card pode reunir várias métricas e avaliar cores por limiares numéricos ou valores exatos, tudo configurado pela interface gráfica.

O módulo não depende do template de monitoramento web. Esse template é apenas uma integração pronta e opcional; o widget também pode representar ping, perda de pacotes, armazenamento, links, servidores, telefonia e outros itens.

### Instalação rápida

```bash
git clone https://github.com/danielrc10/zabbix-dynamic-status-cards.git
cd zabbix-dynamic-status-cards/zabbix-7.4
sudo ./scripts/install_dynamic_status_cards.sh --dry-run
sudo ./scripts/install_dynamic_status_cards.sh
```

Para atualizar:

```bash
git -C zabbix-dynamic-status-cards pull --ff-only
cd zabbix-dynamic-status-cards/zabbix-7.4
sudo ./scripts/install_dynamic_status_cards.sh
```

### Versões testadas

| Versão do Zabbix | Versão do módulo | Estado | Documentação e arquivos |
|---|---:|---|---|
| 7.4 | 1.17.1 | Em validação | [Abrir versão 7.4](zabbix-7.4/README.md) |

## English

Independent module for creating generic status cards on Zabbix dashboards. Each card can combine multiple metrics and evaluate colors through numeric thresholds or exact values, all configured from the graphical interface.

The module does not depend on the web monitoring template. That template is only an optional ready-to-use integration; the widget can also represent ping, packet loss, storage, links, servers, telephony, and other items.

### Tested versions

| Zabbix version | Module version | Status | Documentation and files |
|---|---:|---|---|
| 7.4 | 1.17.1 | Testing | [Open version 7.4](zabbix-7.4/README.md#english) |

## Autor e licença / Author and license

**Daniel Carvalho** · [LinkedIn](https://www.linkedin.com/in/daniel-ti/) ·
[danielrc10@gmail.com](mailto:danielrc10@gmail.com)

Licença / License: [PolyForm Noncommercial 1.0.0](LICENSE). Consulte / See [NOTICE.md](NOTICE.md).
