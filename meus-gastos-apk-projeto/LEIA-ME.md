# Meus Gastos – como gerar o APK (sem instalar nada no PC)

1. Crie uma conta grátis em github.com e um repositório novo (privado serve), com o nome que quiser.
2. Envie TODO o conteúdo desta pasta para o repositório (botão "Add file > Upload files"; arraste a pasta .github também, ou crie o arquivo .github/workflows/apk.yml pelo site).
3. No repositório, aba **Actions** > "Gerar APK" > **Run workflow**. Leva ~5 minutos.
4. Abra a execução concluída, role até **Artifacts** e baixe "meus-gastos-apk" (zip com o app-debug.apk).
5. No celular: abra o .apk e permita "instalar de fontes desconhecidas" quando pedir.

Para mudar o app depois, edite www/index.html no GitHub; o APK é gerado de novo.
