# Crack-Password <br />
Cracker de senhas utilizando Shell. <br />
Algoritmos aceitos: base64, md5, shal, sha256, sha512. <br />

# Uso <br />
Uso: ./crack_password.sh <br />
<br />
## OPÇÕES <br />

-h, --help\t\t\t Exibe este menu de ajuda. <br />
-v, --version\t\t Versão do programa. <br />
-H, --hash\t\t\t Hash a ser quebrado. <br />
-a, --alg\t\t\t Recebe o nome do algoritmo de criptografia. <br />
-w, --wordlist\t\t Recebe um arquivo contendo uma lista de senhas. <br />

## Exemplo: <br />
./crack_password.sh -h <br />
./crack_password.sh -v <br /> 
./crack_password.sh -a base64 -H hash ===> HASHs no formato BASE64 não precisam de wordlist <br />
./crack_password.sh -a md5 -H hash -w wordlist.txt <br />
./crack_password.sh -a shal -H hash -w wordlist.txt <br />
