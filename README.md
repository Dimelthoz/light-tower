# light-tower
Projeto Light Tower para ESP32

- Para mudar as configurações se deve exportar um código binário pela própria IDE do arduino.
- Assim atualizando o fmw.bin da pasta por outro fmw.bin.
- Sempre atualizando o FIRMWARE_VERSION e o raw.txt para terem o mesmo valor, assim podendo atualizar o fmw para o ESP.
- Necessita-se de um certificado de root para essas alterações.
- Quando for utilizar a URL para enviar ao ESP, deve-se mandar no seguinte formato: https://raw.githubusercontent.com/Usuário/Repositório/main/arquivo.txt ou arquivo.bin.
- Sempre quando for pegar o código RAW do arquivo tem que retirar o "blob" da URL.
