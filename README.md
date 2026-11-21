# Lagos Serviços de Transporte 🚐

Aplicativo de gestão da frota e das finanças da empresa: lançamentos de
despesas e receitas, controle de quilometragem, veículos, manutenção,
motoristas e alertas de vencimentos.

## Ficha

- **Abrir:** https://gustavodga.github.io/Lagos/ (Safari → Compartilhar → Adicionar à Tela de Início)
- **Quem usa:** os três sócios, cada um com login próprio
- **Onde ficam os dados:** Firebase próprio (`lagos-operacional`), login por e-mail e senha. Configuração em [SETUP.md](SETUP.md), regras em `firestore.rules`.
- **Publicação:** GitHub Pages, a cada push na `main`. Sem etapa de build.

PWA estático (HTML/CSS/JS puro) — instala direto pela tela inicial do celular.
Acesso restrito aos sócios da empresa.
