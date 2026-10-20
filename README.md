# Arcalon-Updates

Official Arcalon Launcher and Game Updates.

## Instalar Arcalon

1. Para a primeira instalação, baixe o [instalador base do Arcalon](https://github.com/Rhapytor/Arcalon-Updates/releases/download/v5.1.0.2/Arcalon-Setup-5.1.0.2.exe).
2. Execute o instalador. Ele instala o launcher e a Gameplay juntos, com o ícone oficial e atalhos.
3. Abra o Arcalon: ele baixa automaticamente a versão mais recente antes do login.

**Já tem o Arcalon instalado?** Basta fechar e abrir pelo mesmo atalho. Não precisa reinstalar nem copiar arquivos manualmente. As [atualizações recentes](https://github.com/Rhapytor/Arcalon-Updates/releases/latest) podem conter somente o ZIP e o manifesto, sem um novo instalador.

A instalação é por usuário e não solicita administrador. O launcher verifica as atualizações antes de liberar o login. Quando necessário, baixa e atualiza o launcher e a Gameplay, preservando as configurações e a sessão salva.

Os arquivos ZIP e `arcalon-update.json` da release são utilizados pelo atualizador; não é necessário extraí-los para a primeira instalação.

## Versão de testes

- O servidor de jogo ainda utiliza a rede Radmin configurada para os testes.
- O instalador ainda não possui assinatura digital de código; o Windows pode indicar editor desconhecido.
- Este repositório distribui os binários do cliente. Não contém o banco PocketBase, o servidor, senhas ou credenciais administrativas.

## Atualizações

Cada atualização estável usa uma tag de quatro números (`v5.1.0.3`, por exemplo) e contém ZIP completo e manifesto com tamanho/SHA-256. O instalador base é reutilizado; não é gerado novamente a cada atualização. Mudanças são publicadas em uma nova versão, sem substituir os arquivos de uma versão já publicada.
