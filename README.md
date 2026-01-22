# 🎯 DayZ Configuração do servidor - Código Vermelho

Repositório de configurações do servidor **Código Vermelho** da Heptagon.

---

## 📁 Estrutura do Repositório

```
DayZ_Settings_interno_548155297_CodigoVermelho/
├── mpmissions/                    # Configurações de missões
│   └── dayzOffline.chernarusplus/
├── profiles/                      # Perfis e configurações
├── server.yml                     # Configuração principal
├── deploy-history.md              # Histórico de deploys (automático)
└── README.md                      # Este arquivo
```

---

## ⚙️ Configuração Principal

### Arquivo `server.yml`
Contém todas as configurações do servidor:
- **Paths:** Localizações de pastas no servidor físico
- **Backup:** Configuração do sistema de backup
- **Service:** URLs da API do Omega Manager
- **Metadata:** Informações sobre o servidor

### Modificações
Para alterar configurações do servidor:
1. Edite os arquivos em `mpmissions/` ou `profiles/`
2. Faça commit das alterações
3. Solicite deploy via administrador Heptagon

---

## 🔄 Histórico de Deploys

O arquivo [deploy-history.md](deploy-history.md) é atualizado automaticamente após cada deploy e contém por exemplo:

ex:
| Versão | Tipo | Data | Status |
|--------|------|------|--------|
| 2025-12-01_10-30_INCREMENTAL | INCREMENTAL | 2025-12-01 10:30:00 | Concluído |
| 2025-12-01_14-45_WIPEFULL | WIPEFULL | 2025-12-01 14:45:00 | Concluído |

**Para rollback:** Use o ID da versão (ex: `2025-12-01_10-30_INCREMENTAL`)

---

## 🚀 Como Solicitar Deploys

### Atualizações de Configuração:
1. Faça suas alterações neste repositório
2. Crie um Pull Request ou commite na branch `Master`
3. Entre em contato com a administração Heptagon
4. Solicite deploy do tipo:
   - **INCREMENTAL:** Para mudanças sem limpar dados dos jogadores
   - **WIPEFULL:** Para nova temporada (limpa todos os dados)

### Rollback (Emergência):
1. Identifique a versão estável em `deploy-history.md`
2. Solicite rollback informando o ID da versão
3. Administração executa o processo

---

## 📊 Informações do Servidor

- **Nome:** CodigoVermelho
- **Tipo:** PVP (Player vs Player)
- **Mapa:** Chernarus Plus
- **Mods:** Airdrop-Upgrade, VanillaPlusPlusMap, Advance Weapon Scopes, Forward Operator Gear, MuchFramework, MuchStuffPack, SNAFU_Weapons, AC-Mod-Pack, BuilderItems, SchanaParty, ReducedFireWeaponsDamage, DayZRedux, ZT Vending Machine, Banking, Trader Mod, Codelock, VppAdminTools, Community Framework.
- **Cliente:** Jhonathan (externo)
- **Host:** WH001

---

## 🔒 Segurança

- Este repositório é **privado**
- Apenas administradores Heptagon e pessoal autorizado têm acesso
- Tokens e credenciais NÃO devem ser commitados
- Use variáveis no `server.yml` para dados sensíveis

---

## 🆘 Suporte

### Para questões técnicas:
- Entre em contato com a equipe Heptagon
- Referencie este repositório nas issues
- Consulte `deploy-history.md` para histórico de mudanças

---

## 📄 Observações

- Todas as mudanças são versionadas via Git
- Backups automáticos são feitos antes de cada deploy
- O sistema é gerenciado pelo framework Heptagon DayZ Manager
- Para mudanças complexas, consulte a documentação principal

---

**Última Atualização:** Dezembro 2025  
**Responsável:** Administração Heptagon  
**Status do Servidor:** 🔴 Offline
