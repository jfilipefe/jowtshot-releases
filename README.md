# JowtShot — Releases

Binários e feed de atualização automática (Sparkle) do **JowtShot** — app de captura
de tela para macOS, leve, em português, gratuito e open-source.

## Instalar

1. Baixe o `JowtShot-x.y.z.zip` do release mais recente e descompacte.
2. Arraste `JowtShot.app` para `/Applications`.
3. Como o app ainda não é notarizado pela Apple, na primeira abertura use
   **botão direito → Abrir**, ou rode:
   ```bash
   xattr -dr com.apple.quarantine /Applications/JowtShot.app
   ```
4. Conceda a permissão em **Ajustes do Sistema → Privacidade e Segurança →
   Gravação de Tela**.

As atualizações seguintes chegam **automaticamente** pelo próprio app (Sparkle).

## Verificação

Cada release inclui o `SHA256` do arquivo. O feed de atualização é assinado
com EdDSA (a chave pública está embutida no app).

---
© 2026 Jordy Filipe · Licença MIT
