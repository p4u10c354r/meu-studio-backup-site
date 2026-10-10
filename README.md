# Meu Studio Backup — site informativo

Este repositório público contém apenas a página inicial e a política de privacidade da integração privada do **Meu Studio Backup** com o Google Drive.

**Nunca adicione a este repositório credenciais, tokens OAuth, dados de alunos, código interno do sistema ou arquivos de backup.**

## Publicar no GitHub Pages

1. Abra **Settings → Pages** neste repositório.
2. Em **Build and deployment → Source**, selecione **Deploy from a branch**.
3. Em **Branch**, selecione **main** e **/(root)**, e clique em **Save**.
4. Quando a publicação estiver concluída, confirme os seguintes endereços:
   - Página inicial: https://p4u10c354r.github.io/meu-studio-backup-site/
   - Política de privacidade: https://p4u10c354r.github.io/meu-studio-backup-site/privacidade.html
5. Apenas após testar os links, use-os nos campos de **Branding** do aplicativo OAuth no Google Cloud.

## Segurança

Este site é apenas informativo: não conecta o visitante ao Google Drive, não autentica alunos e não expõe os backups.

O aplicativo OAuth e as credenciais da rotina de backup ficam configurados separadamente. O workflow de backup deve permanecer manual até passar pelos testes de exportação, verificação de integridade e restauração isolada.
