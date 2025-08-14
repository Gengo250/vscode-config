# VS Code — Minhas Configurações (Gengo)

**Arquivos incluídos**
- `settings.json`
- `keybindings.json`
- `snippets/`
- `extensions.txt`

## Como aplicar em outra máquina (Windows)
1. Feche o VS Code.
2. Copie `settings.json`, `keybindings.json` e a pasta `snippets/` para:
   `C:\Users\<SEU_USUARIO>\AppData\Roaming\Code\User\`
3. Abra o VS Code.
4. Instale as extensões:
   ```powershell
   Get-Content extensions.txt | ForEach-Object { code --install-extension $_ }
