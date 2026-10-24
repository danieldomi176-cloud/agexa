# Free My TV para Android

[Descarregar o pacote Windows](./FreeMyTV-Windows.zip?raw=true) — inclui o APK, as ferramentas ADB oficiais Google e os passos de procura e instalação local.

[Descarregar apenas o APK](./FreeMyTV.apk?raw=true).

O APK foi compilado de [simbasjungles/free-my-tv](https://github.com/simbasjungles/free-my-tv), commit `4d739516379976e4cc256e4106f3680d6bb94da8`, versão Android 1.1. A assinatura APK v2/v3 foi verificada. Requer Android 8 ou posterior. A execução dos scripts no Windows e o funcionamento na TV ainda precisam de validação local.

Extraia todo o ZIP no Windows. Ligue o PC e a TV ao mesmo Wi-Fi, abra `1-Procurar-TVs.cmd` para procurar dispositivos e consulte `LEIA-ME.txt` antes de usar `2-Instalar-FreeMyTV.cmd`. É necessário ativar a depuração ADB pela rede na TV e aceitar nela o pedido de autorização. O instalador mostra fabricante/modelo e pede confirmação antes de instalar. O IP anterior, `192.168.1.253`, pode ter mudado.

É uma aplicação de ecrã inicial: não substitui o Android nem atualiza o firmware. O instalador não muda o ecrã inicial automaticamente. Não inclui chave TMDB; a cidade e meteorologia ainda têm os valores de exemplo do projeto. Para futuras atualizações é necessário conservar a mesma chave de assinatura, que não está incluída neste download. Não desinstale versões anteriores para contornar erros de assinatura.

As ferramentas Google e as respetivas licenças acompanham o ZIP. Os hashes dos ficheiros estão em [SHA256SUMS.txt](./SHA256SUMS.txt).
